<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xap50hwvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xap50hwvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-group-bold" /></template>
