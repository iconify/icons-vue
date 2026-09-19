<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il_265byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="il_265byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gong" /></template>
