<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/fiqwvobaq.css';
import '../../css/f/fckq11bbx.css';
import '../../css/g/go6zdtbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fiqwvobaq"/><path clip-rule="evenodd" class="fckq11bbx"/><path class="go6zdtbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coffee-sharp-duotone" /></template>
