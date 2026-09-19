<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmmp82b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kmmp82b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:droplet-outline" /></template>
