<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soouwnbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="soouwnbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:adjust-outline" /></template>
