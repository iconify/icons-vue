<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz17a-bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz17a-bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-on-square-solid" /></template>
