<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6q6ctlhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y6q6ctlhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:gift-box" /></template>
