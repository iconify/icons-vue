<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptk_gpb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ptk_gpb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-0" /></template>
