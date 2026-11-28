<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a25g90ajj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/ss8t1tbbv.css';
import '../../css/r/rh3g6zbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a25g90ajj secondary"/><g class="dt0cm9dhy primary"><path class="ss8t1tbbv"/><path class="rh3g6zbdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmark-check-duo" /></template>
