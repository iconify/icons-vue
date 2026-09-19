<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1uf30h9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r1uf30h9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chest-armor" /></template>
