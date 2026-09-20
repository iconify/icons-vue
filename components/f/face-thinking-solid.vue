<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjph59xfl.css';
import '../../css/p/pg557kbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjph59xfl"/><path class="pg557kbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-thinking-solid" /></template>
