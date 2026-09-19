<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cstvsf11p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="cstvsf11p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:button-sell" /></template>
