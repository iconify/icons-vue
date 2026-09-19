<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm15w3b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qm15w3b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:axe-sword" /></template>
