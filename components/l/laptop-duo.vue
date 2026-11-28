<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi-0n8byp.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/ydkjijhaq.css';
import '../../css/y/yq2tbpldz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi-0n8byp secondary"/><g class="dt0cm9dhy primary"><path class="ydkjijhaq"/><path class="yq2tbpldz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:laptop-duo" /></template>
