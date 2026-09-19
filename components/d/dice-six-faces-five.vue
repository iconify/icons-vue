<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmzko8bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kmzko8bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dice-six-faces-five" /></template>
