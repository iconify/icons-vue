<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhvt2-bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xhvt2-bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-earth-outline" /></template>
