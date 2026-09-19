<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr4ur_7jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mr4ur_7jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fog-1-bold" /></template>
