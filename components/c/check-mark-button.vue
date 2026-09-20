<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5e2kbc5z.css';
import '../../css/h/ho0k_acab.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/i/ijy0jnbrd.css';
import '../../css/i/i64oqpblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="d5e2kbc5z"/><path class="ho0k_acab"/><g class="ij2x_72vy"><path class="ijy0jnbrd"/><path class="i64oqpblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:check-mark-button" /></template>
