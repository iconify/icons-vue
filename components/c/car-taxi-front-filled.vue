<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe3n-sdlk.css';
import '../../css/m/m_0bwy7ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qe3n-sdlk"/><path class="m_0bwy7ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:car-taxi-front-filled" /></template>
