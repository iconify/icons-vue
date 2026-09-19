<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv2c4yb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wv2c4yb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:evil-wings" /></template>
