<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/ts44bdc2p.css';
import '../../css/d/d9vkjnbmf.css';
import '../../css/r/rrslsmpft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ts44bdc2p"/><path class="d9vkjnbmf"/><path class="rrslsmpft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cpu" /></template>
