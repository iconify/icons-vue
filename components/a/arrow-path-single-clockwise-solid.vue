<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l70_i177h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l70_i177h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-clockwise-solid" /></template>
