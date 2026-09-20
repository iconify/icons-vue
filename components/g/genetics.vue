<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1gw67brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h1gw67brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:genetics" /></template>
