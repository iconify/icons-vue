<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6cjc0bct.css';
import '../../css/q/qao-31brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v6cjc0bct"/><path class="qao-31brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-global" /></template>
