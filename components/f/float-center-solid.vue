<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqq0ivbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hqq0ivbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:float-center-solid" /></template>
