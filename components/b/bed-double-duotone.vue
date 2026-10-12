<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w2c_h5xxn.css';
import '../../css/w/wvwdkcb2e.css';
import '../../css/u/u2vuu1tco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w2c_h5xxn"/><path class="wvwdkcb2e"/><path class="u2vuu1tco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bed-double-duotone" /></template>
