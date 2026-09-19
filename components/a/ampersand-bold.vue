<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2pai4fwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="n2pai4fwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ampersand-bold" /></template>
