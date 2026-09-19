<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-qp-ebuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-qp-ebuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:great-war-tank" /></template>
