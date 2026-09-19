<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc_a0bb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kc_a0bb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:arrow-top" /></template>
