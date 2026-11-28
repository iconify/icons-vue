<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joeh75boo.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mw5qx4brw.css';
import '../../css/v/v_kf02dmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joeh75boo secondary"/><g class="dt0cm9dhy primary"><path class="mw5qx4brw"/><path class="v_kf02dmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:game-cartridge-duo" /></template>
