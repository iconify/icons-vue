<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeju42bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeju42bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:location-arrow" /></template>
