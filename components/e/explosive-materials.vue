<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts5kodb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ts5kodb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:explosive-materials" /></template>
