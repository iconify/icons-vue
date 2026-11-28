<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msk0mniql.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b66ewmbkg.css';
import '../../css/n/n5qfzup1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msk0mniql secondary"/><g class="dt0cm9dhy primary"><path class="b66ewmbkg"/><path class="n5qfzup1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-rain-duo" /></template>
