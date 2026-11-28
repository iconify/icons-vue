<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d3--f9bxt.css';
import '../../css/l/l6185mb2v.css';
import '../../css/s/ssxb6oabf.css';
import '../../css/a/a7exq6baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d3--f9bxt"/><path class="l6185mb2v"/><path class="ssxb6oabf"/><path class="a7exq6baw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:collapse-duo" /></template>
