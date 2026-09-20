<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4s8ktvhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4s8ktvhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:element4-filled" /></template>
