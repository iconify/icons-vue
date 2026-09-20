<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p94_bsqsn.css';
import '../../css/s/s4tzz1xjy.css';
import '../../css/k/k7i5r8b-m.css';
import '../../css/b/buvterbpv.css';
import '../../css/v/v6a9_t-6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p94_bsqsn"/><path class="s4tzz1xjy"/><path class="k7i5r8b-m"/><path class="buvterbpv"/><path class="v6a9_t-6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:donation-charity-donate-bag-2" /></template>
