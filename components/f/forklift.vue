<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz5r0vbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz5r0vbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:forklift" /></template>
