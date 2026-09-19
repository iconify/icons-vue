<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnlsoq3zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gnlsoq3zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:circle-half-full" /></template>
