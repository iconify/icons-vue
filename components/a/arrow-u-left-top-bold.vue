<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm_tufblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm_tufblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-left-top-bold" /></template>
