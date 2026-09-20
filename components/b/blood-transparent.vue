<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy5egbc5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy5egbc5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:blood-transparent" /></template>
