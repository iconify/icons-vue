<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9q-umbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9q-umbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bow-string" /></template>
