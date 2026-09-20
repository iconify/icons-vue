<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0y-3vblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0y-3vblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:anilist" /></template>
