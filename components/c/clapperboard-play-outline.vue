<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uurj7xe-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uurj7xe-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-play-outline" /></template>
