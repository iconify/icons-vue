<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rko2k9b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rko2k9b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:button-tv" /></template>
