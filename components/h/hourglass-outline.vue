<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq0w_7b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cq0w_7b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hourglass-outline" /></template>
