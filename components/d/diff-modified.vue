<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0emlsjte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="r0emlsjte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-modified" /></template>
