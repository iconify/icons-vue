<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hjk15qw-b.css';
import '../../css/r/rbyek3b2v.css';
import '../../css/y/yxph-hmed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="hjk15qw-b"/><path vector-effect="non-scaling-stroke" class="rbyek3b2v"/><path vector-effect="non-scaling-stroke" class="yxph-hmed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-list-numbered" /></template>
