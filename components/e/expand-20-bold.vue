<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mli097arj.css';
import '../../css/c/c9abqnf6w.css';
import '../../css/q/qzu82cbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mli097arj"/><path class="c9abqnf6w"/><path class="qzu82cbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:expand-20-bold" /></template>
