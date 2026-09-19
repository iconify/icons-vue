<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s52to77mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s52to77mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:a-outline" /></template>
