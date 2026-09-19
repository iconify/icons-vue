<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgf5uvnvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vgf5uvnvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:carnivorous-plant" /></template>
