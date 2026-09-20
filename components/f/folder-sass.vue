<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqup61b4d.css';
import '../../css/r/rr671wplb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oqup61b4d"/><path class="rr671wplb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-sass" /></template>
