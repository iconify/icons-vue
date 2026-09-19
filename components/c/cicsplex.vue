<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy2kxn1ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oy2kxn1ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cicsplex" /></template>
