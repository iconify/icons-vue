<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf7qg7_ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bf7qg7_ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chevron-right" /></template>
