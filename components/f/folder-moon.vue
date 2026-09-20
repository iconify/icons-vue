<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6_kf7bqk.css';
import '../../css/u/u86f3_xou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l6_kf7bqk"/><path class="u86f3_xou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-moon" /></template>
