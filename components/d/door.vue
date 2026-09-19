<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vva03ib8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vva03ib8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:door" /></template>
