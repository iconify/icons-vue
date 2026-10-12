<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lj_w8hblv.css';
import '../../css/o/okc6r4m0z.css';
import '../../css/n/ns0x3kbdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lj_w8hblv"/><path class="okc6r4m0z"/><path class="ns0x3kbdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:balloon-duotone" /></template>
