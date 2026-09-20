<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8o3-m2zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dishwasher-outline-sharp" /></template>
<style>
.n8o3-m2zw {
  fill: currentColor;
  d: path("M5 10.385V19h14v-8.615zm0-1h14V5H5zm7 8.115q-.633 0-1.066-.443q-.434-.444-.434-1.095q0-.598.356-1.332T12 12.923q.789.993 1.144 1.717t.356 1.322q0 .652-.434 1.095q-.433.443-1.066.443m5.549-9.951q.22-.22.22-.549t-.22-.549t-.549-.22t-.549.22t-.22.549t.22.549t.549.22t.549-.22M4 20V4h16v16zM5 9.385V5z");
}

</style>
