<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nup4ibcwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="nup4ibcwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:book-person" /></template>
