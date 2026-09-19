<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g4y7acbjs.css';
import '../../css/i/iod4a0bly.css';
import '../../css/l/ldby4ccie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="g4y7acbjs"/><path clip-rule="evenodd" class="iod4a0bly"/><path clip-rule="evenodd" class="ldby4ccie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:credit-card-print" /></template>
