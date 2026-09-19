<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/j850wac-i.css';
import '../../css/n/n56_8z4jg.css';
import '../../css/o/ofkbvnbsv.css';
import '../../css/z/z6z3uibua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="j850wac-i"/><path class="n56_8z4jg"/><circle class="ofkbvnbsv"/><circle class="z6z3uibua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:engineering-vehicle" /></template>
