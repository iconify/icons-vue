<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h7yrl6lbb.css';
import '../../css/w/w6xc5vbzb.css';
import '../../css/r/rf_lmqdyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h7yrl6lbb"/><path class="w6xc5vbzb"/><path class="rf_lmqdyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:kangaroo" /></template>
