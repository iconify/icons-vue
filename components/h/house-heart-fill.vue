<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5kggccsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5kggccsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:house-heart-fill" /></template>
