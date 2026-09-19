<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1y_2yb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":661};
const content = `<path class="q1y_2yb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:car" /></template>
