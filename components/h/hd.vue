<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_y9lkb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_y9lkb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:hd" /></template>
