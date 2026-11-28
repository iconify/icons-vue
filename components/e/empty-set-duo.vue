<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb559801h.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pnfk9ob5j.css';
import '../../css/t/t4-a8ebgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb559801h secondary"/><g class="dt0cm9dhy primary"><path class="pnfk9ob5j"/><path class="t4-a8ebgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:empty-set-duo" /></template>
