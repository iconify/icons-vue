<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xemudqboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="xemudqboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bomb-1" /></template>
