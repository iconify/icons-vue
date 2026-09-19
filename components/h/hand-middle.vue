<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6rtj7bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="y6rtj7bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-middle" /></template>
