<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjqj9n19a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cjqj9n19a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:easal" /></template>
