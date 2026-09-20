<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsp2tpz6a.css';
import '../../css/w/wjbqyhpxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qsp2tpz6a"/><path class="wjbqyhpxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cross-mark" /></template>
