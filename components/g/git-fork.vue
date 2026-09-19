<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz5z4w1dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2560,"height":2048};
const content = `<path class="fz5z4w1dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:git-fork" /></template>
