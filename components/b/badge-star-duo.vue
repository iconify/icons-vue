<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djhm11b9z.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/x/xeq28t4zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djhm11b9z secondary"/><g class="dt0cm9dhy primary"><path class="l4--ovbba"/><path class="xeq28t4zp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-star-duo" /></template>
