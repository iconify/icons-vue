<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh2rg2bpe.css';
import '../../css/i/i9gf5actf.css';
import '../../css/e/e2wi94ygl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":140,"height":140};
const content = `<g transform="translate(10.508 10.205)" class="sh2rg2bpe"><circle class="i9gf5actf"/><path class="e2wi94ygl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:browserlist-light" /></template>
