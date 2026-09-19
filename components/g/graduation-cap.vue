<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k2nt8ab-v.css';
import '../../css/q/qm9y-abir.css';
import '../../css/x/x-pqprbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="k2nt8ab-v"/><path class="qm9y-abir"/><path class="x-pqprbxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:graduation-cap" /></template>
