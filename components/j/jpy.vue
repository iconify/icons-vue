<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_h1abcbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n_h1abcbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:jpy" /></template>
