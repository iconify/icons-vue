<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpujgzbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpujgzbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:equalizer-duotone-round" /></template>
