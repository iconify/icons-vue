<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/itm5al3co.css';
import '../../css/t/tytsexmko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="itm5al3co"/><path clip-rule="evenodd" class="tytsexmko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-9-fill" /></template>
