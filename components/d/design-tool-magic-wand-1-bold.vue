<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdcs0-b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdcs0-b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-tool-magic-wand-1-bold" /></template>
