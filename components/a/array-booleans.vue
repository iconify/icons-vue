<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfdmkubzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rfdmkubzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:array-booleans" /></template>
