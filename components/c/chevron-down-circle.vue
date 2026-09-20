<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf6nn3bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf6nn3bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-down-circle" /></template>
