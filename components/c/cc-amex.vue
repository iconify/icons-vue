<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhnivs28x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="mhnivs28x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cc-amex" /></template>
