<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkmf2zbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkmf2zbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ary" /></template>
