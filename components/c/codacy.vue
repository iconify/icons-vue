<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exm6s8_rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="exm6s8_rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:codacy" /></template>
