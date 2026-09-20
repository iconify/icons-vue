<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqiwjybyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqiwjybyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:keyboard-music" /></template>
