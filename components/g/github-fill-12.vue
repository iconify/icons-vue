<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jves9ubuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jves9ubuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:github-fill-12" /></template>
