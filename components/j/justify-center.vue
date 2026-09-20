<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a660lgbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a660lgbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:justify-center" /></template>
