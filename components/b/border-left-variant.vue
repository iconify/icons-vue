<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aro9nj3gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aro9nj3gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:border-left-variant" /></template>
