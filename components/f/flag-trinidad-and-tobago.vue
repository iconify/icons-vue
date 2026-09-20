<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8cxt48ie.css';
import '../../css/x/xjykb7bad.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><path class="xjykb7bad"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-trinidad-and-tobago" /></template>
