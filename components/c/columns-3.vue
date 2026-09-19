<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4f2uacmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s4f2uacmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:columns-3" /></template>
