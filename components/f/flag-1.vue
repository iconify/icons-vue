<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjpbn_mym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jjpbn_mym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:flag-1" /></template>
