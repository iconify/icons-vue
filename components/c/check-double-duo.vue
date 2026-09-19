<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb24vgbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pb24vgbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check-double-duo" /></template>
