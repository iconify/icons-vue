<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p71m-ys5l.css';
import '../../css/z/zjq1ew06h.css';
import '../../css/o/of-4y9qcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p71m-ys5l"/><path class="zjq1ew06h"/><path class="of-4y9qcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:bag-suitcase-4-flat" /></template>
