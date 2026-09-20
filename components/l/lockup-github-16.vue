<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo62x3btp.css';
import '../../css/g/g8ck1ubmr.css';
import '../../css/g/gktvaxxcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":68,"height":16};
const content = `<path class="qo62x3btp"/><path class="g8ck1ubmr"/><path class="gktvaxxcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:lockup-github-16" /></template>
