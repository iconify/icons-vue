<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/syanz0xqe.css';
import '../../css/m/mrca2uc4y.css';
import '../../css/r/r72cq5izs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="syanz0xqe"/><path class="mrca2uc4y"/><path class="r72cq5izs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:knot" /></template>
