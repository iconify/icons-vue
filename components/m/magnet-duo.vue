<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhurrtb2s.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o2-_brbuv.css';
import '../../css/k/kxz1mg-ky.css';
import '../../css/l/limh9cbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhurrtb2s secondary"/><g class="dt0cm9dhy primary"><path class="o2-_brbuv"/><path class="kxz1mg-ky"/><path class="limh9cbhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:magnet-duo" /></template>
