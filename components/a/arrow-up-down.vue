<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huyx0gevn.css';
import '../../css/l/lmzjhacao.css';
import '../../css/w/wqefnac-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huyx0gevn"/><path class="lmzjhacao"/><path class="wqefnac-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-up-down" /></template>
