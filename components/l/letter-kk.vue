<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jytyqbb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jytyqbb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-kk" /></template>
