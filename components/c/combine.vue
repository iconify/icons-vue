<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/lk887tbfi.css';
import '../../css/t/td4pmbm2c.css';
import '../../css/g/gufd03s5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lk887tbfi"/><rect class="td4pmbm2c"/><rect class="gufd03s5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:combine" /></template>
