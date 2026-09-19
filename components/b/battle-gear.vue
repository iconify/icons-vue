<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6c1dbcal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s6c1dbcal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:battle-gear" /></template>
