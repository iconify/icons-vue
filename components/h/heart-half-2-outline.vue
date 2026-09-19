<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ko7b07r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p7ko7b07r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-half-2-outline" /></template>
