<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4cvr9bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e4cvr9bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:libra" /></template>
