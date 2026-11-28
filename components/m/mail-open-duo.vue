<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iban41b3x.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sz9tdkb8m.css';
import '../../css/w/wbhiowbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iban41b3x secondary"/><g class="dt0cm9dhy primary"><path class="sz9tdkb8m"/><path class="wbhiowbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mail-open-duo" /></template>
