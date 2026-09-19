<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of5620y8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="of5620y8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:candy" /></template>
