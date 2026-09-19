<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcsl11xbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qcsl11xbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:black-book" /></template>
