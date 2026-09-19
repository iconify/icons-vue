<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpupu3bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1312};
const content = `<path class="jpupu3bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:home" /></template>
