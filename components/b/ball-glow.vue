<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0uz5ld-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b0uz5ld-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ball-glow" /></template>
