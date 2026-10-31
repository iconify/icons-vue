<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy610kn7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy610kn7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-grab-fill-round" /></template>
