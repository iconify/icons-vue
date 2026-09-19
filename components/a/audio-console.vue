<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oogoxknap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oogoxknap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:audio-console" /></template>
