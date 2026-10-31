<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og742qsmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og742qsmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:close-small-duotone-round" /></template>
