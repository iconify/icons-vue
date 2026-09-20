<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxen_1b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-back-ios-rounded" /></template>
<style>
.vxen_1b6n {
  fill: currentColor;
  d: path("m2.82 12l7.715 7.716q.22.22.218.528t-.224.529t-.529.221t-.529-.221L1.83 13.137q-.242-.243-.354-.54q-.111-.299-.111-.597t.111-.596q.112-.298.354-.54L9.47 3.22q.221-.221.532-.218q.31.003.532.224q.22.221.22.529t-.22.529z");
}

</style>
