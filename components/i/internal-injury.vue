<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz3g6ebxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vz3g6ebxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:internal-injury" /></template>
