<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5ahj8bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g5ahj8bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:fuel-pump-fill" /></template>
