<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fli0rkblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fli0rkblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-compare-2-fill" /></template>
