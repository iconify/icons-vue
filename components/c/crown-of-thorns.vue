<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lisoj4jki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lisoj4jki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crown-of-thorns" /></template>
