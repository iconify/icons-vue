<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy_bwvbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy_bwvbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-charging-fill-round" /></template>
