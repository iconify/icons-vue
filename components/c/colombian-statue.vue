<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztli60bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztli60bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:colombian-statue" /></template>
