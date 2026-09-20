<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zimqkib2m.css';
import '../../css/y/y1jfbyb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zimqkib2m"/><path class="y1jfbyb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:magnifier" /></template>
