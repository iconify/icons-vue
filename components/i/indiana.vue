<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb16_pbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kb16_pbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:indiana" /></template>
