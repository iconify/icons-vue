<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbuc5572w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mbuc5572w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:badge-outline" /></template>
