<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0akcpbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v0akcpbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:magnet-outline" /></template>
