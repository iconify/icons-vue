<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nzgqy2toz.css';
import '../../css/u/uadr4mbak.css';
import '../../css/o/o35n15qhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nzgqy2toz"/><path class="uadr4mbak"/><path class="o35n15qhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-arc" /></template>
