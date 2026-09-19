<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngqy7dzmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ngqy7dzmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:black-knight-helm" /></template>
