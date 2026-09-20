<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlrtktw0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:glass-cup-outline" /></template>
<style>
.qlrtktw0d {
  fill: currentColor;
  d: path("M6.975 22q-.775 0-1.337-.5T5 20.225L3 2h18l-2 18.225q-.075.775-.638 1.275t-1.337.5zm-.2-4L7 20h10l.225-2zm-.2-2H17.45l1.3-12H5.25zm.2 4h10.45z");
}

</style>
