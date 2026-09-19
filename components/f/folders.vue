<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op7a0sdgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="op7a0sdgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folders" /></template>
