<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl_di5buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="gl_di5buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check-double" /></template>
