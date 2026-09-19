<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uf6sm2mwe.css';
import '../../css/p/pdimccbtd.css';
import '../../css/o/olw7yj8qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="uf6sm2mwe"/><path class="pdimccbtd"/><path class="olw7yj8qe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-download" /></template>
