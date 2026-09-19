<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9ul_lbcj.css';
import '../../css/r/r32kt6-tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="f9ul_lbcj"/><path class="r32kt6-tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:archive" /></template>
