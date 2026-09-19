<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/roz0gr1al.css';
import '../../css/b/bti7b4bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="roz0gr1al"/><path class="bti7b4bab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-audacity" /></template>
