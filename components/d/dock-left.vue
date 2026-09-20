<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-t9hbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-t9hbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dock-left" /></template>
