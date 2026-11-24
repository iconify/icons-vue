<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pds1fv54u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:control-tower-fill-round" /></template>
<style>
.pds1fv54u {
  fill: currentColor;
  d: path("M13 3v3h6c.285 0 .563.076.806.225c1.009.624.939 2.073.629 3.064a4.9 4.9 0 0 1-.603 1.266l-2 3A1 1 0 0 1 17 14h-1v6h5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h5v-6H7a1 1 0 0 1-.832-.445l-2-3a4.9 4.9 0 0 1-.603-1.266c-.31-.991-.38-2.44.629-3.064C4.437 6.076 4.715 6 5 6h6V3a1 1 0 0 1 2 0m-5.465 9h1.078L7.279 8h-1.41a.535.535 0 0 0-.446.832Zm5.744 0l1.334-4H9.387l1.334 4Zm2.108 0h1.078l1.703-2.555l.001-.001l.408-.612A.536.536 0 0 0 18.131 8h-1.41Z");
}

</style>
