<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojtv12bfi.css';
import '../../css/b/b2qas0b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ojtv12bfi"/><path class="b2qas0b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:accumulation-ice" /></template>
