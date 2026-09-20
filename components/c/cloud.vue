<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhwli594r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jhwli594r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud" /></template>
