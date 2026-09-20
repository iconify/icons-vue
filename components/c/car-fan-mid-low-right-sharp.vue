<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by0emyblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-fan-mid-low-right-sharp" /></template>
<style>
.by0emyblm {
  fill: currentColor;
  d: path("m9.802 22l-.86-.52l3.66-5.73h4.34l1.624-5.64q.192-.644.636-1.031t1.006-.387q.777 0 1.28.596t.354 1.372l-1.419 7.032h-7.625zM20.519 7.692q-.613 0-1.037-.424t-.424-1.037t.424-1.038t1.037-.424t1.038.424t.424 1.038t-.424 1.037t-1.038.424m-9.23 2.212l-.708-.708l2.902-2.927H7.019v-1h6.445l-2.902-2.902l.727-.713l4.115 4.115zm-5.173 8.48L2 14.27l.694-.688l2.902 2.902l.02-6.483h1v6.444l2.907-2.882l.727.707z");
}

</style>
