<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myvgeabpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="myvgeabpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:broad-dagger" /></template>
