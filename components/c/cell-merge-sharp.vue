<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suvnrxilp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cell-merge-sharp" /></template>
<style>
.suvnrxilp {
  fill: currentColor;
  d: path("M3 21v-6h2v4h4v2zm12 0v-2h4v-4h2v6zm-7.825-5.175l-1.425-1.4L7.175 13H2v-2h5.175L5.75 9.575l1.425-1.4L11 12zm9.65 0L13 12l3.825-3.825l1.425 1.4L16.825 11H22v2h-5.175l1.425 1.425zM3 9V3h6v2H5v4zm16 0V5h-4V3h6v6z");
}

</style>
