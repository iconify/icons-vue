<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he7924bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="he7924bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:gradle-logo-32" /></template>
