<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/g9qe22bnk.css';
import '../../css/z/zizwbwb-u.css';
import '../../css/e/ebnucmg7y.css';
import '../../css/a/aexuozm6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="g9qe22bnk wm-shadow"/><path class="wm-shadow zizwbwb-u"/><path class="ebnucmg7y"/><path class="aexuozm6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:donut" /></template>
