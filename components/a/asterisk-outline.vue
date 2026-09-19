<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3_k9bchf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g3_k9bchf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:asterisk-outline" /></template>
