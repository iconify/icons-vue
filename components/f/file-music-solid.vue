<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jea_kmbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jea_kmbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-music-solid" /></template>
