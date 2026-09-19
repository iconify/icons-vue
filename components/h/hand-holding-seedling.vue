<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgi2v4blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kgi2v4blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-seedling" /></template>
