<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd2dswubh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vd2dswubh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bolt" /></template>
