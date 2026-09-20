<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hjk15qw-b.css';
import '../../css/a/ahy7r9h0a.css';
import '../../css/i/iuvqghvku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="hjk15qw-b"/><path class="ahy7r9h0a"/><path vector-effect="non-scaling-stroke" class="iuvqghvku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-list-bullets" /></template>
