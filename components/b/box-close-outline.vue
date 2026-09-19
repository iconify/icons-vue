<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av9yo2bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="av9yo2bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-close-outline" /></template>
