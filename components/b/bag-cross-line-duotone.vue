<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u04hmj8af.css';
import '../../css/s/shxcjzbfi.css';
import '../../css/m/mw42pob4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u04hmj8af"/><path class="shxcjzbfi"/><path class="mw42pob4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-cross-line-duotone" /></template>
