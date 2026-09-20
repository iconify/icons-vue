<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0mrqv-vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0mrqv-vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-play-outline" /></template>
