<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1nu-xiim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":208};
const content = `<path class="u1nu-xiim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:github-copilot-light" /></template>
