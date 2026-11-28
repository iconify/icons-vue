<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdo3n1bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdo3n1bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-three-quarter-solid" /></template>
