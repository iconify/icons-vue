<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgf-3otpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgf-3otpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:curly-mask" /></template>
