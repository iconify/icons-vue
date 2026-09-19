<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goxbou09t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="goxbou09t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:accumulation-rain" /></template>
