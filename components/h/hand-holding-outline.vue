<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jze5oiupp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jze5oiupp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-outline" /></template>
