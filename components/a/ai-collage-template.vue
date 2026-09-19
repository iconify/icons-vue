<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnvc6abtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnvc6abtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-collage-template" /></template>
