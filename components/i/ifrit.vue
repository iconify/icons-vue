<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2q-jjb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w2q-jjb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ifrit" /></template>
