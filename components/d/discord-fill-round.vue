<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrar2pyxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrar2pyxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:discord-fill-round" /></template>
