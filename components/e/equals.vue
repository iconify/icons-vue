<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo0mn_bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vo0mn_bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:equals" /></template>
