<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpxcr_mnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hpxcr_mnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:flower" /></template>
