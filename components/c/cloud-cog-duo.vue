<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1rz9ybqr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/da92j5b5b.css';
import '../../css/g/go4iz9b_l.css';
import '../../css/z/z78tyulfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1rz9ybqr secondary"/><g class="dt0cm9dhy primary"><path class="da92j5b5b"/><path class="go4iz9b_l"/><path class="z78tyulfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-cog-duo" /></template>
