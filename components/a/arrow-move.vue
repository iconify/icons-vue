<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8y9nwb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t8y9nwb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-move" /></template>
