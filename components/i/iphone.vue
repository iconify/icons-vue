<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha6__qbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ha6__qbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:iphone" /></template>
