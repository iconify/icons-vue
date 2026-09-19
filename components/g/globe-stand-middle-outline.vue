<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8qo2ibht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="o8qo2ibht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-stand-middle-outline" /></template>
