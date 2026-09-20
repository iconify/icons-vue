<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m535sz11f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m535sz11f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:deep-cogito" /></template>
