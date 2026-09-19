<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc9l2mb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wc9l2mb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:glyphs-filled" /></template>
