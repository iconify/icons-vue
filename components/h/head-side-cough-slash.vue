<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8h17jlhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="c8h17jlhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:head-side-cough-slash" /></template>
