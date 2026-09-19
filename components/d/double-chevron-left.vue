<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajqbr35kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ajqbr35kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:double-chevron-left" /></template>
