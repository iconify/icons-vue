<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o__p3qu_u.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nycrbqbau.css';
import '../../css/x/xmwe5fa4e.css';
import '../../css/p/pek5k1b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o__p3qu_u secondary"/><g class="dt0cm9dhy primary"><path class="nycrbqbau"/><path class="xmwe5fa4e"/><path class="pek5k1b2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-mail-duo" /></template>
