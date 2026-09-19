<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg_bf7b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vg_bf7b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:game-emoji" /></template>
