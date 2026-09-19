<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr_fj5b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="sr_fj5b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:club" /></template>
