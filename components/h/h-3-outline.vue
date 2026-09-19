<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db2bucbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="db2bucbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-3-outline" /></template>
