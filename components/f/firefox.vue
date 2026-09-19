<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_372t7wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t_372t7wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:firefox" /></template>
