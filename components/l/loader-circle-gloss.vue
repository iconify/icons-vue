<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzydt9bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzydt9bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:loader-circle-gloss" /></template>
