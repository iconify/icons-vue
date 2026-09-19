<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4j9i0bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4j9i0bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:glaive" /></template>
