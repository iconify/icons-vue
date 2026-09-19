<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw_jc_5dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="iw_jc_5dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-circle-bold" /></template>
