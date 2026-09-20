<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yarq-ooto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yarq-ooto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:loading-3" /></template>
