<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apkel7bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="apkel7bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:calculator-multiply" /></template>
