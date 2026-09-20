<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/ssmkz5zlu.css';
import '../../css/n/npzbi206w.css';
import '../../css/m/m-2o9kbye.css';
import '../../css/i/ivi_x117u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ssmkz5zlu"/><circle class="npzbi206w"/><circle class="m-2o9kbye"/><circle class="ivi_x117u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chess-queen" /></template>
