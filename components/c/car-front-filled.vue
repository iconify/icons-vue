<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe3n-sdlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qe3n-sdlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:car-front-filled" /></template>
