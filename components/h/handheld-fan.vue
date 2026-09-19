<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzobbd9rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hzobbd9rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:handheld-fan" /></template>
