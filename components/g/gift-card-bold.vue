<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arlvf1h-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="arlvf1h-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gift-card-bold" /></template>
