<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4up2objj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4up2objj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:expansion-card-variant" /></template>
