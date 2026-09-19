<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evfpsd44e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="evfpsd44e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:crop" /></template>
