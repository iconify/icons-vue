<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0fkrdwdb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ll59ytbdg.css';
import '../../css/r/r7w21kpsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0fkrdwdb secondary"/><g class="dt0cm9dhy primary"><path class="ll59ytbdg"/><path class="r7w21kpsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:automation-duo" /></template>
