<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u13p1nbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="u13p1nbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:emoticon" /></template>
