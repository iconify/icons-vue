<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbslk5mju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qbslk5mju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dice-six-faces-six" /></template>
