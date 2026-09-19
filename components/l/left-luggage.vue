<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw13r8b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw13r8b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:left-luggage" /></template>
