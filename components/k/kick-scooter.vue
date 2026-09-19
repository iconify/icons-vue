<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny3uyebdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ny3uyebdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kick-scooter" /></template>
