<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2gdbkbzv.css';
import '../../css/d/dn50i0run.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2gdbkbzv"/><path class="dn50i0run"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-jinja" /></template>
