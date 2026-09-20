<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/ketgzibwl.css';
import '../../css/q/qeti59buh.css';
import '../../css/x/xqwhzubqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ketgzibwl"/><path class="qeti59buh"/><path class="xqwhzubqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:cashier-machine-2-flat" /></template>
