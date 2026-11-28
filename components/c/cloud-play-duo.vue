<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bicqxs2zz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/da92j5b5b.css';
import '../../css/y/y4m964bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bicqxs2zz secondary"/><g class="dt0cm9dhy primary"><path class="da92j5b5b"/><path class="y4m964bqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-play-duo" /></template>
