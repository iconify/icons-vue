<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9lec6bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9lec6bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right" /></template>
