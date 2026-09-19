<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sesq7venk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sesq7venk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:acid-blob" /></template>
