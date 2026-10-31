<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rctcusbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rctcusbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-left-round" /></template>
