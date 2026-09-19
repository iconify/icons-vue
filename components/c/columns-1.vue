<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxifazq2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rxifazq2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:columns-1" /></template>
