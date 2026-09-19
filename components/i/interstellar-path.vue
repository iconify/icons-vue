<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df8ps71ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="df8ps71ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:interstellar-path" /></template>
