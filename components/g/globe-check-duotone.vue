<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/its8f7byw.css';
import '../../css/j/j4t0g_avv.css';
import '../../css/i/im-u2lvxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="its8f7byw"/><path class="j4t0g_avv"/><path class="im-u2lvxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-check-duotone" /></template>
