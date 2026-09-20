<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpl65cc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rpl65cc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:delivery" /></template>
