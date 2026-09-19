<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scsbrkeec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="scsbrkeec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:laser-warning" /></template>
