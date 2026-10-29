<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m8nybubas.css';
import '../../css/g/g9g2iobxb.css';
import '../../css/o/o7ull5bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="m8nybubas"/><path class="g9g2iobxb wm-a"/><path class="o7ull5bnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:coffee-duo" /></template>
