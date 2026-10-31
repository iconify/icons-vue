<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6509kg3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6509kg3l wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-compare-gloss" /></template>
