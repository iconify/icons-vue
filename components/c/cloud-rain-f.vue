<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l7y7ddcjv.css';
import '../../css/t/tp_md9bnt.css';
import '../../css/u/uch44xcum.css';
import '../../css/l/lkoadtbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="l7y7ddcjv"/><rect class="tp_md9bnt"/><rect class="uch44xcum"/><rect class="lkoadtbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cloud-rain-f" /></template>
