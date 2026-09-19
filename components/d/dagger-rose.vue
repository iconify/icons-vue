<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0v512beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t0v512beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dagger-rose" /></template>
