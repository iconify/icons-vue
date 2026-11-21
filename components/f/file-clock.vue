<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/boz1ay-3b.css';
import '../../css/m/mno380iqb.css';
import '../../css/s/syp171bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="boz1ay-3b"/><path class="mno380iqb"/><circle class="syp171bgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:file-clock" /></template>
