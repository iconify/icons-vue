<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spnx_mb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spnx_mb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bagpipes" /></template>
