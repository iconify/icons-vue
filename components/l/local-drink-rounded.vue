<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey8so8b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-drink-rounded" /></template>
<style>
.ey8so8b3n {
  fill: currentColor;
  d: path("M7.475 21q-.626 0-1.08-.407t-.53-1.022L4.14 4.283q-.067-.52.288-.901Q4.782 3 5.308 3h13.384q.526 0 .88.382q.355.382.288.9l-1.706 15.29q-.075.615-.53 1.021t-1.08.407zM5.592 8.385h12.835L18.866 4H5.116zm8.077 9.051q.681-.679.681-1.667q0-.967-.582-1.885q-.581-.917-1.134-1.647q-.118-.171-.285-.247q-.168-.075-.349-.075t-.348.076t-.286.246q-.552.73-1.134 1.647q-.582.918-.582 1.885q0 .988.68 1.667t1.67.68t1.67-.68");
}

</style>
