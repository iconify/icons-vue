<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzrh2j4yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jzrh2j4yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:git-repo" /></template>
