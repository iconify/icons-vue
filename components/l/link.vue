<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr75xkbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pr75xkbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:link" /></template>
