<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suju9flbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suju9flbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:audio-wave-01" /></template>
