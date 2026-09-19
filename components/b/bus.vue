<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cakb5klrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cakb5klrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bus" /></template>
