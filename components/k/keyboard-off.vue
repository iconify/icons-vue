<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joxwt1bet.css';
import '../../css/k/kdd-004ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="joxwt1bet"/><path class="kdd-004ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:keyboard-off" /></template>
