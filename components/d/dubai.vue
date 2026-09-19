<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/yj73g48oj.css';
import '../../css/u/udaafzcol.css';
import '../../css/i/ii0wlebwq.css';
import '../../css/v/vlfpiv6el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="yj73g48oj"/><path class="udaafzcol"/><path class="ii0wlebwq"/><path class="vlfpiv6el"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:dubai" /></template>
