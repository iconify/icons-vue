<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/czeiw6b4w.css';
import '../../css/p/p_64ncbxo.css';
import '../../css/s/sfrj7abtj.css';
import '../../css/j/jpb-3cbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="czeiw6b4w"/><path class="p_64ncbxo"/><path class="sfrj7abtj"/><path class="jpb-3cbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-line-duotone" /></template>
