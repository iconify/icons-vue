<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk511mbit.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/if_fr7tub.css';
import '../../css/e/exnkhlvdn.css';
import '../../css/v/v686tqbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk511mbit secondary"/><g class="dt0cm9dhy primary"><path class="if_fr7tub"/><path class="exnkhlvdn"/><path class="v686tqbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-area-stacked-duo" /></template>
