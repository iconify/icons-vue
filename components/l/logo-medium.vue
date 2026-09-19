<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prv40i33l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="prv40i33l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-medium" /></template>
