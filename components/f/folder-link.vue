<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6_kf7bqk.css';
import '../../css/n/nwovjeb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l6_kf7bqk"/><path class="nwovjeb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-link" /></template>
