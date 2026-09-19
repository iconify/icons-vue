<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0t_jjb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r0t_jjb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-africa-outline" /></template>
