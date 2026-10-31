<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lqg1sds5j.css';
import '../../css/s/sjok7_pru.css';
import '../../css/r/rgpp5pbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lqg1sds5j"/><path class="sjok7_pru"/><path class="rgpp5pbiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ball-wave-duotone" /></template>
