<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on_u07ckd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="on_u07ckd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:align-justify" /></template>
