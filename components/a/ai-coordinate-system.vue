<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w2jxh9fwj.css';
import '../../css/b/b7i2f0z9m.css';
import '../../css/l/ldpo4n3qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w2jxh9fwj"/><path class="b7i2f0z9m"/><path class="ldpo4n3qb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-coordinate-system" /></template>
