<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byvrfmb7t.css';
import '../../css/r/rw1w1gbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="byvrfmb7t"/><path class="rw1w1gbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:brick" /></template>
