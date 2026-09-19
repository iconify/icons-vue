<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy_-jrb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cy_-jrb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:conversation" /></template>
