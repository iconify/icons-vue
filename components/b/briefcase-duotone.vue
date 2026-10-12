<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hyt0gbcxe.css';
import '../../css/f/flf5bgbgb.css';
import '../../css/q/qp_f2rhnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hyt0gbcxe"/><path class="flf5bgbgb"/><path class="qp_f2rhnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:briefcase-duotone" /></template>
