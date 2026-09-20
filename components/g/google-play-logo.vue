<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg36jbbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg36jbbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-play-logo" /></template>
