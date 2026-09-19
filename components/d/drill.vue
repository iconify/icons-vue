<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_ms1__zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_ms1__zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:drill" /></template>
