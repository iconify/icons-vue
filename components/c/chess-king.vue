<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fos04kb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fos04kb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chess-king" /></template>
