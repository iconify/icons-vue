<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3yj_uvhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r3yj_uvhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:exclamation-circle-bold" /></template>
