<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-mw4h6ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-mw4h6ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:horned-skull" /></template>
