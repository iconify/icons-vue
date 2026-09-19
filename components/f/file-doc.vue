<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6m59nb7p.css';
import '../../css/y/yyfpz7bxh.css';
import '../../css/o/oiejv2yqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6m59nb7p"/><path class="yyfpz7bxh"/><path class="oiejv2yqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-doc" /></template>
