<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp8n6hb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lp8n6hb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:browser-chrome" /></template>
