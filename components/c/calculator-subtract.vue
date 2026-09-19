<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia3709bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ia3709bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:calculator-subtract" /></template>
