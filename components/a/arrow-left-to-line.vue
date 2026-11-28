<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h3rqpkjxm.css';
import '../../css/p/pbhf4ibgw.css';
import '../../css/l/lv1lbhbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h3rqpkjxm"/><path class="pbhf4ibgw"/><path class="lv1lbhbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-left-to-line" /></template>
