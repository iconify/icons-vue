<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gasy4njrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gasy4njrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aspect-ratio-fill-round" /></template>
