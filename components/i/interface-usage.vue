<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcn9ecb-z.css';
import '../../css/f/f-7sbkbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dcn9ecb-z"/><path class="f-7sbkbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:interface-usage" /></template>
