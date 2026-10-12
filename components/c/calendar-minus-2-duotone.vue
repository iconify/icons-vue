<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k_94w8q1x.css';
import '../../css/p/p3poopb-f.css';
import '../../css/a/ayqei1lop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k_94w8q1x"/><path class="p3poopb-f"/><path class="ayqei1lop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-minus-2-duotone" /></template>
