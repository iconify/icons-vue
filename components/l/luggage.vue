<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7765vlsl.css';
import '../../css/q/q51k3abci.css';
import '../../css/k/ke4xsybbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7765vlsl wm-k"/><path class="q51k3abci wm-k"/><path class="ke4xsybbc wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:luggage" /></template>
