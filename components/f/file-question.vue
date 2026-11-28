<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_gmhcswf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_gmhcswf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-question" /></template>
