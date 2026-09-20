<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sp2fbb8bo.css';
import '../../css/c/cpy0n4a_h.css';
import '../../css/i/isx5y3bfo.css';
import '../../css/f/fa1iec66m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sp2fbb8bo"/><path class="cpy0n4a_h"/><path class="isx5y3bfo"/><path class="fa1iec66m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:horizontal-toggle-button-flat" /></template>
