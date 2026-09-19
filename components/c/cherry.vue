<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq4a1cc0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rq4a1cc0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cherry" /></template>
