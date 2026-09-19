<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi84yvodx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xi84yvodx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:canoe-2" /></template>
