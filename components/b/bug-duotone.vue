<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/adwzh7blz.css';
import '../../css/o/oaeva_b0f.css';
import '../../css/t/t10a2509h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="adwzh7blz"/><path class="oaeva_b0f"/><path class="t10a2509h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bug-duotone" /></template>
