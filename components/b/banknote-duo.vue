<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7c2ymwll.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sb-u7hbtr.css';
import '../../css/f/fn1xrabpt.css';
import '../../css/y/yodla97la.css';
import '../../css/k/k-foczbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7c2ymwll secondary"/><g class="dt0cm9dhy primary"><path class="sb-u7hbtr"/><circle class="fn1xrabpt"/><path class="yodla97la"/><path class="k-foczbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:banknote-duo" /></template>
