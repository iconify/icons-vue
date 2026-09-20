<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz0z2xbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz0z2xbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ipod" /></template>
