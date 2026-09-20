<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi9dt8sqd.css';
import '../../css/q/qxuya4bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vi9dt8sqd"/><path class="qxuya4bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-proto-open" /></template>
