<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/parsp50es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="parsp50es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:come" /></template>
