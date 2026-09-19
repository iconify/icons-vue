<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpyzt7bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zpyzt7bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bleeding-wound" /></template>
