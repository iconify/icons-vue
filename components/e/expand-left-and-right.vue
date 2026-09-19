<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsx0ls6vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsx0ls6vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:expand-left-and-right" /></template>
