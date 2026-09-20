<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdg671b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdg671b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:downscale" /></template>
