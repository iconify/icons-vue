<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx6oijbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tx6oijbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:item-usage" /></template>
