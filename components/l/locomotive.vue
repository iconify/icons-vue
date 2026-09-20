<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz6sfydxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz6sfydxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:locomotive" /></template>
