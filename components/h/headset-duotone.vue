<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y-49kub1n.css';
import '../../css/l/l3ti7bc2l.css';
import '../../css/z/z-7f7hehn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y-49kub1n"/><path class="l3ti7bc2l"/><path class="z-7f7hehn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:headset-duotone" /></template>
