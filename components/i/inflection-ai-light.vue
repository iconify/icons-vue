<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oywncb5to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oywncb5to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inflection-ai-light" /></template>
