<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqrx59q5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lqrx59q5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dragonfly" /></template>
