<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phq3-bb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="phq3-bb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bell-dot-light" /></template>
