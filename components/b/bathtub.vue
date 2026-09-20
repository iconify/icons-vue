<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lymybh1aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lymybh1aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bathtub" /></template>
