<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdilbsbas.css';
import '../../css/z/z05git9xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdilbsbas"/><path class="z05git9xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flag-chequered" /></template>
