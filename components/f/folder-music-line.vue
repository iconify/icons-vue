<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1_dzw0-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1_dzw0-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-music-line" /></template>
