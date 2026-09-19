<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v444rac2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v444rac2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cda" /></template>
