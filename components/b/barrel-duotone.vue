<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uew948jvc.css';
import '../../css/r/r155nbcpm.css';
import '../../css/x/xkosiwb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uew948jvc"/><path class="r155nbcpm"/><path class="xkosiwb3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:barrel-duotone" /></template>
