<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lumw3fbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lumw3fbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:leaf-outline" /></template>
