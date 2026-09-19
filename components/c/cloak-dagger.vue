<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg81n9b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wg81n9b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cloak-dagger" /></template>
