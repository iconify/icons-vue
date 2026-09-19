<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib_cetbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ib_cetbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dice-fire" /></template>
