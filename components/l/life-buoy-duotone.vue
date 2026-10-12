<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ukp0h0bby.css';
import '../../css/h/h31rlcbji.css';
import '../../css/m/mb3gk9bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ukp0h0bby"/><path class="h31rlcbji"/><path class="mb3gk9bpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:life-buoy-duotone" /></template>
