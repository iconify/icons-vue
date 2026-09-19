<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpx0u7qjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wpx0u7qjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-open-outline" /></template>
