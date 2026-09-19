<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc1enib9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="oc1enib9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dot-mark" /></template>
