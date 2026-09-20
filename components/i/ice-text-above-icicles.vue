<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtsflpb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xtsflpb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ice-text-above-icicles" /></template>
