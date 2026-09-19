<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex2v2vb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ex2v2vb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:github" /></template>
