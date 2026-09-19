<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ngehmsigm.css';
import '../../css/k/k44e6hbrh.css';
import '../../css/x/x2xhq2bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><rect class="ngehmsigm"/><path clip-rule="evenodd" class="k44e6hbrh"/><path class="x2xhq2bdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:leave-print" /></template>
