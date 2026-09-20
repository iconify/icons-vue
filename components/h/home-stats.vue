<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/l6xmiu9yl.css';
import '../../css/b/b_dk99s4m.css';
import '../../css/s/ssw2-urzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l6xmiu9yl"/><path class="b_dk99s4m"/><path class="ssw2-urzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:home-stats" /></template>
