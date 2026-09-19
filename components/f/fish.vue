<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n42l-qbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="n42l-qbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:fish" /></template>
