<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcbz_pozm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mcbz_pozm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-outline" /></template>
