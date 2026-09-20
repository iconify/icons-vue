<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehy3bccpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ehy3bccpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:basket-plus-outline" /></template>
