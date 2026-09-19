<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv8z3-74d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":697,"height":768};
const content = `<path class="yv8z3-74d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:coffee" /></template>
