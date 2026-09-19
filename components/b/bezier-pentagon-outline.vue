<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzv1a95zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pzv1a95zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-pentagon-outline" /></template>
