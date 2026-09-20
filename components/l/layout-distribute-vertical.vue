<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttw2t9byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttw2t9byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-distribute-vertical" /></template>
