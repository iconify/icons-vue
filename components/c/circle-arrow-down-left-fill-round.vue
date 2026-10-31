<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjiq25bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjiq25bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-down-left-fill-round" /></template>
