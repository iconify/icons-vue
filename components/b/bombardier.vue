<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyciayb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyciayb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bombardier" /></template>
