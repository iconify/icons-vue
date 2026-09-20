<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="intyp8b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dishwasher-sharp" /></template>
<style>
.intyp8b2i {
  fill: currentColor;
  d: path("M5 10.385V19h14v-8.615zm7 7.115q-.633 0-1.066-.443q-.434-.444-.434-1.095q0-.598.356-1.332T12 12.923q.789.993 1.144 1.717t.356 1.322q0 .652-.434 1.095q-.433.443-1.066.443m5.549-9.951q.22-.22.22-.549t-.22-.549t-.549-.22t-.549.22t-.22.549t.22.549t.549.22t.549-.22M4 20V4h16v16z");
}

</style>
