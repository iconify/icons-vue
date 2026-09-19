<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4gi4cv0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v4gi4cv0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:key" /></template>
