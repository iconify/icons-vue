<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux5i6zjqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ux5i6zjqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:christmass-ball" /></template>
