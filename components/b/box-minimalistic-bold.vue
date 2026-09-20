<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/la--7ib8h.css';
import '../../css/e/e06ot6o4h.css';
import '../../css/k/k85dgg62q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="la--7ib8h"/><path class="e06ot6o4h"/><path class="k85dgg62q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:box-minimalistic-bold" /></template>
