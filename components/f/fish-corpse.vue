<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_7av-bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_7av-bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fish-corpse" /></template>
