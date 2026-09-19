<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep54zkxas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="ep54zkxas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:locked-filled" /></template>
