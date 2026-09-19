<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oigkvhr6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oigkvhr6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:heavy-lightning" /></template>
