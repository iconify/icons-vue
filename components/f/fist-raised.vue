<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kampcngpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kampcngpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fist-raised" /></template>
