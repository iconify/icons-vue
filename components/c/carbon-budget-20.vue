<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj3g4qi-v.css';
import '../../css/f/fcca0vb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jj3g4qi-v"/><path class="fcca0vb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-budget-20" /></template>
