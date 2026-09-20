<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a09_lptpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a09_lptpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-down-fill" /></template>
