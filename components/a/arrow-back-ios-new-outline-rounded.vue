<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8q025bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-back-ios-new-outline-rounded" /></template>
<style>
.f8q025bvt {
  fill: currentColor;
  d: path("m8.82 12l7.715 7.716q.22.22.218.528t-.224.529q-.221.221-.529.221t-.529-.221L7.83 13.136q-.243-.242-.354-.54q-.112-.298-.112-.596t.112-.596t.354-.54l7.64-7.644q.221-.221.532-.218q.31.003.531.224t.222.529t-.222.528z");
}

</style>
