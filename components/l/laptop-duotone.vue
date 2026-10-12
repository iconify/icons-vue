<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v_ltqvfxc.css';
import '../../css/k/ktey3n4hx.css';
import '../../css/f/frm1azcsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v_ltqvfxc"/><path class="ktey3n4hx"/><path class="frm1azcsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:laptop-duotone" /></template>
