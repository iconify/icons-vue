<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/c/c1qs2i.css';
import '../../css/a/axqjwt.css';
import '../../css/z/zt_tcx.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c c1qs2i"/><path class="a0m25c axqjwt"/><path class="a0m25c zt_tcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-triple-right" /></template>
