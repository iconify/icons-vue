<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r38g2ac-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r38g2ac-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:king-ju-mask" /></template>
