<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o_-qtrbgi.css';
import '../../css/p/p3poopb-f.css';
import '../../css/h/hxngk6b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o_-qtrbgi"/><path class="p3poopb-f"/><path class="hxngk6b1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-plus-duotone" /></template>
