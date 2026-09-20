<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/ee7yp3btr.css';
import '../../css/t/tg_riobvo.css';
import '../../css/t/tj6aivbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ee7yp3btr"/><path class="tg_riobvo"/><ellipse class="tj6aivbzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:database-arrow-down" /></template>
