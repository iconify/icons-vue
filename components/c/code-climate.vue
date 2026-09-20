<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6nnlgbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="a6nnlgbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:code-climate" /></template>
