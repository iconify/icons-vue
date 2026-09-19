<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdk7pcc_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xdk7pcc_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bolt" /></template>
