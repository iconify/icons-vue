<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as8au5_4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="as8au5_4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cabbage" /></template>
