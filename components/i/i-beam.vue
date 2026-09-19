<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8-jom4ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8-jom4ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:i-beam" /></template>
