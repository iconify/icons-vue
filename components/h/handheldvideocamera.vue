<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es97rtbpl.css';
import '../../css/m/mhn45ibqb.css';
import '../../css/m/m2897mb0i.css';
import '../../css/z/zk30aempb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="es97rtbpl"/><path class="mhn45ibqb"/><circle class="m2897mb0i"/><path class="zk30aempb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:handheldvideocamera" /></template>
