<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezpns49_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezpns49_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-pen-line" /></template>
