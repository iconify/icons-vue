<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyxz16ioe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyxz16ioe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ibeacon" /></template>
