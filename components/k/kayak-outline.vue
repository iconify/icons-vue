<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0s98rd3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z0s98rd3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:kayak-outline" /></template>
