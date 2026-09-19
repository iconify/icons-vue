<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_qw5gr9p.css';
import '../../css/y/yrfreqb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_qw5gr9p"/><path class="yrfreqb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:external-link" /></template>
