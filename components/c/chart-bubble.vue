<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgpzimtyu.css';
import '../../css/c/cshvu2rwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hgpzimtyu"/><path class="cshvu2rwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-bubble" /></template>
