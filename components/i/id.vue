<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2k_9ab2j.css';
import '../../css/b/bfvbc4b-j.css';
import '../../css/h/hz6ugwsiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c2k_9ab2j"/><path class="bfvbc4b-j"/><path class="hz6ugwsiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:id" /></template>
