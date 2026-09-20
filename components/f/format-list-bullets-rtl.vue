<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m3q5dgd3j.css';
import '../../css/u/u7o5kg02o.css';
import '../../css/p/p2fb2ojkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="m3q5dgd3j"/><path class="u7o5kg02o"/><path vector-effect="non-scaling-stroke" class="p2fb2ojkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-list-bullets-rtl" /></template>
