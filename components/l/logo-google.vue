<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3qskuahn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z3qskuahn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-google" /></template>
