<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1v_3z4yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p1v_3z4yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heart-key" /></template>
