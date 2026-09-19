<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9u81yn3y.css';
import '../../css/c/c_2y2ytjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="i9u81yn3y"/><path class="c_2y2ytjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:git-commit-outline" /></template>
