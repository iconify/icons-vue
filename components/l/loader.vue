<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/bg2fqfxmz.css';
import '../../css/q/q_h3vjbce.css';
import '../../css/c/co_a6dbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="bg2fqfxmz wm-shadow"/><path class="q_h3vjbce wm-shadow"/><path class="co_a6dbew"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:loader" /></template>
