<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw5_x3b-j.css';
import '../../css/j/jzkzakb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zw5_x3b-j"/><path class="jzkzakb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:leftwards-hand-light-skin-tone" /></template>
