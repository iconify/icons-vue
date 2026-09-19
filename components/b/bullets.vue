<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_dx_-bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_dx_-bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bullets" /></template>
