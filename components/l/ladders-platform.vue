<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz-bcgoml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tz-bcgoml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ladders-platform" /></template>
