<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abbf3ujbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="abbf3ujbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:euro" /></template>
