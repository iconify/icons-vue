<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q6s3x3npd.css';
import '../../css/x/x2u6flxpt.css';
import '../../css/n/ncu-jmblv.css';
import '../../css/p/pmz70xezp.css';
import '../../css/l/lxa0s2bjs.css';
import '../../css/n/n8akoezgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q6s3x3npd"/><path class="x2u6flxpt"/><path class="ncu-jmblv"/><path class="pmz70xezp"/><path class="lxa0s2bjs"/><path class="n8akoezgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:barcode-scan-bold-duotone" /></template>
