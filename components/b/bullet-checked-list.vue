<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxq95pbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pxq95pbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bullet-checked-list" /></template>
