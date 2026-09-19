<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-adjnplt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-adjnplt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flying-fox" /></template>
