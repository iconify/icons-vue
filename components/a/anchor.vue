<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqm0ns9os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="gqm0ns9os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:anchor" /></template>
