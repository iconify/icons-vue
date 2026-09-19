<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf14otbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qf14otbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:collapse" /></template>
