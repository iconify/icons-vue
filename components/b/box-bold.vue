<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk352rb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bk352rb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-bold" /></template>
