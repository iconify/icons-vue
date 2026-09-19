<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghf65hbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghf65hbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:aerial-signal" /></template>
