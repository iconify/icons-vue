<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u48mzcbuj.css';
import '../../css/j/jx1k9cbwn.css';
import '../../css/h/hpqa_4g6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u48mzcbuj"/><path class="jx1k9cbwn"/><path class="hpqa_4g6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-lefthook-open" /></template>
