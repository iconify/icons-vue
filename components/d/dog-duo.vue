<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhvs046gs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/ynh-y4bge.css';
import '../../css/y/y53y7edxy.css';
import '../../css/e/e_baxktzp.css';
import '../../css/h/hljsh5bsw.css';
import '../../css/e/e6juojboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xhvs046gs"/><g class="dt0cm9dhy primary"><path class="ynh-y4bge"/><path class="y53y7edxy"/><path class="e_baxktzp"/><path class="hljsh5bsw"/><path class="e6juojboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dog-duo" /></template>
