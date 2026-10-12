<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n7cad7v2b.css';
import '../../css/d/d2_ueooqs.css';
import '../../css/f/fe81k0bsy.css';
import '../../css/o/okcbgs62p.css';
import '../../css/y/ysz-f3b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n7cad7v2b"/><path class="d2_ueooqs"/><path class="fe81k0bsy"/><path class="okcbgs62p"/><path class="ysz-f3b-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-minus-duotone" /></template>
