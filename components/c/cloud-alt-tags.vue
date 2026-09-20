<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/p/pmw-rr.css';
import '../../css/h/h-ksjc.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fade-to-1.css';
import '../../css/s/so-from-6.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c pmw-rr"/><path class="a0m25c h-ksjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:cloud-alt-tags" /></template>
