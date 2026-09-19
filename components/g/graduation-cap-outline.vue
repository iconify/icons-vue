<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3lsmi_yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y3lsmi_yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:graduation-cap-outline" /></template>
