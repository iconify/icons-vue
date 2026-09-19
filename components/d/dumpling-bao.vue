<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdrdouc4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdrdouc4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dumpling-bao" /></template>
