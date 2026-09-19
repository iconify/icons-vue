<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_84t1yuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="f_84t1yuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-2-bold" /></template>
