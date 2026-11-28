<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw79mfk2v.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mdipw5bzh.css';
import '../../css/m/m1ue8zbct.css';
import '../../css/v/vmu_hmryr.css';
import '../../css/h/h-32pdodc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw79mfk2v secondary"/><g class="dt0cm9dhy primary"><path class="mdipw5bzh"/><path class="m1ue8zbct"/><path class="vmu_hmryr"/><path class="h-32pdodc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-user-duo" /></template>
