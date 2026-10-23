<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkjmfib4i.css';
import '../../css/s/s2r542g-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkjmfib4i"/><path class="s2r542g-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-fading-play-filled" /></template>
