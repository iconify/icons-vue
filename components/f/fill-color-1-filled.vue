<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwsi43bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwsi43bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fill-color-1-filled" /></template>
