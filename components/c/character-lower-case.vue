<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh_q1tzxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gh_q1tzxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:character-lower-case" /></template>
