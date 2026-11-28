<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au00--b_v.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e090hdc7h.css';
import '../../css/y/ylliqbbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au00--b_v secondary"/><g class="dt0cm9dhy primary"><path class="e090hdc7h"/><path class="ylliqbbkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gallery-horizontal-end-duo" /></template>
