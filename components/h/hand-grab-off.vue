<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xyjtgccot.css';
import '../../css/g/gl1k5hr6v.css';
import '../../css/m/ml6dupy2r.css';
import '../../css/k/k4t3lsbvd.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="xyjtgccot"><path clip-rule="evenodd" class="gl1k5hr6v"/><path class="ml6dupy2r"/></g><path clip-rule="evenodd" class="k4t3lsbvd"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:hand-grab-off" /></template>
