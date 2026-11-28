<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r029m-boa.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a12an581p.css';
import '../../css/k/kbxpyqdun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r029m-boa secondary"/><g class="dt0cm9dhy primary"><path class="a12an581p"/><path class="kbxpyqdun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chess-queen-duo" /></template>
