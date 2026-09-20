<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i5et97u9j.css';
import '../../css/d/d8p9rg9qy.css';
import '../../css/t/tkq4zwbvg.css';
import '../../css/t/ti1egob9t.css';
import '../../css/w/wm3p8rb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i5et97u9j"/><path class="d8p9rg9qy"/><path class="tkq4zwbvg"/><path class="ti1egob9t"/><path class="wm3p8rb_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-vertical-line-duotone" /></template>
