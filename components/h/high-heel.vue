<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3884ntkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x3884ntkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:high-heel" /></template>
