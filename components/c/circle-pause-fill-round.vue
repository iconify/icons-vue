<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnq1vmbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnq1vmbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-pause-fill-round" /></template>
