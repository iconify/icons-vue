<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbopo_bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jbopo_bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flat-paw-print" /></template>
