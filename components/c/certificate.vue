<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjqv8bbgf.css';
import '../../css/r/rp7qrtb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cjqv8bbgf"/><path class="rp7qrtb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:certificate" /></template>
