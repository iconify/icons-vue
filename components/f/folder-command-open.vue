<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da1i54d5m.css';
import '../../css/z/z3y6h9b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="da1i54d5m"/><path class="z3y6h9b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-command-open" /></template>
