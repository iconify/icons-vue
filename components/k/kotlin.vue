<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd25emlxv.css';
import '../../css/z/zesgwkbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bd25emlxv"/><path class="zesgwkbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:kotlin" /></template>
