<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-uzi_0xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l-uzi_0xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:escalators" /></template>
