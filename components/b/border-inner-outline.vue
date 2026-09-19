<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxc2vnb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dxc2vnb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-inner-outline" /></template>
