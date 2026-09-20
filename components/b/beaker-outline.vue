<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am5ozhb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am5ozhb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-outline" /></template>
