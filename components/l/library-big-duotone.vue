<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ihe_8ubmh.css';
import '../../css/j/jfxb75zwt.css';
import '../../css/t/thtwgkblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ihe_8ubmh"/><path class="jfxb75zwt"/><path class="thtwgkblz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:library-big-duotone" /></template>
