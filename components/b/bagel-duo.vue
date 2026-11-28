<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxp_pxb9n.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/z/z0iw1obqm.css';
import '../../css/d/d5l4gdc1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxp_pxb9n secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="z0iw1obqm"/><path class="d5l4gdc1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bagel-duo" /></template>
