<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihdg2ibts.css';
import '../../css/j/jzkzakb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ihdg2ibts"/><path class="jzkzakb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:leftwards-hand-medium-skin-tone" /></template>
