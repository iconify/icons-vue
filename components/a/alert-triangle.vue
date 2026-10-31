<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/b3w0adc3y.css';
import '../../css/h/hh62rlb-m.css';
import '../../css/d/dqvt27bhn.css';
import '../../css/h/hlaue6blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="b3w0adc3y wm-shadow"/><path class="hh62rlb-m wm-shadow"/><path class="dqvt27bhn"/><path class="hlaue6blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:alert-triangle" /></template>
