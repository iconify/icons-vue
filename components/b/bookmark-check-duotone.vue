<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cwaw64b1u.css';
import '../../css/p/p395msbuh.css';
import '../../css/k/kx1bn5j4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cwaw64b1u"/><path class="p395msbuh"/><path class="kx1bn5j4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bookmark-check-duotone" /></template>
