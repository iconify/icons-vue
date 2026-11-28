<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpt0mldnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpt0mldnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-search" /></template>
