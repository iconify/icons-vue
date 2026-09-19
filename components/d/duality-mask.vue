<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mytyl3bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mytyl3bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:duality-mask" /></template>
