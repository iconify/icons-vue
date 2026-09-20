<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/xtsrmvj7o.css';
import '../../css/p/p9vjoqtlo.css';
import '../../css/u/u8b1jwb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="xtsrmvj7o"/><circle class="p9vjoqtlo"/><path class="u8b1jwb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:diameter" /></template>
