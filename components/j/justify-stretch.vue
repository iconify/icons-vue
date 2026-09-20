<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ldh1adcqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ldh1adcqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:justify-stretch" /></template>
