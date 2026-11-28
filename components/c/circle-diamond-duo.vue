<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdtgmubkg.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/h/h63l7kbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdtgmubkg secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="h63l7kbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-diamond-duo" /></template>
