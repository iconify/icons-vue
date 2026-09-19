<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzfw7cc9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzfw7cc9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:caveman" /></template>
