<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qml99rnqd.css';
import '../../css/i/imcjgjb4f.css';
import '../../css/f/flzkd7s7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qml99rnqd"/><path class="imcjgjb4f"/><path class="flzkd7s7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-locked-16" /></template>
