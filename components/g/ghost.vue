<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d7ntyebyk.css';
import '../../css/a/a0e2ybb-k.css';
import '../../css/l/l9z_5vbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d7ntyebyk"/><path class="a0e2ybb-k"/><path class="l9z_5vbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ghost" /></template>
