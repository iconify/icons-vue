<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1n-zwboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i1n-zwboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-womens-health" /></template>
