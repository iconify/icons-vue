<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jb-grt_jm.css';
import '../../css/o/o8joigbba.css';
import '../../css/o/o3uru2bok.css';
import '../../css/t/tt2xjccpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jb-grt_jm"/><path class="o8joigbba"/><path class="o3uru2bok"/><path class="tt2xjccpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:crypto-currency-bitcoin-chip" /></template>
