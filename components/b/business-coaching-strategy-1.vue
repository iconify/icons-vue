<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/ab-2i5bvk.css';
import '../../css/r/rh8_bp6fq.css';
import '../../css/z/zdl4vfpnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ab-2i5bvk"/><path class="rh8_bp6fq"/><path class="zdl4vfpnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:business-coaching-strategy-1" /></template>
