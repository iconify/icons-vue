<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx7fwobyf.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/k/kmp12_cmj.css';
import '../../css/c/cnp20ep5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bx7fwobyf"/><g class="jn8qy4bru"><path class="kmp12_cmj"/><path class="cnp20ep5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:home-button" /></template>
