<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u21_yhbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u21_yhbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cc-jcb" /></template>
