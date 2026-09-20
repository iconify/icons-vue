<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju0ktzb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:featured-seasonal-and-gifts" /></template>
<style>
.ju0ktzb_u {
  fill: currentColor;
  d: path("M4.23 21V10.23H3V5.809h5.142q-.298-.264-.412-.625q-.114-.362-.114-.76q0-.993.695-1.689T10 2.039q.575 0 1.056.27q.48.27.829.703q.348-.439.828-.706t1.056-.267q.994 0 1.69.695t.695 1.689q0 .39-.118.753t-.409.632H21v4.423h-1.23V21zm8.558-17.563q-.403.398-.403.986t.398.987t.986.398t.987-.398t.398-.987t-.403-.986t-.982-.398t-.982.398m-4.172.986q0 .589.403.987t.982.398t.982-.398t.403-.987t-.399-.986T10 3.039t-.986.398t-.398.986M4 6.808V9.23h7.5V6.808zM11.5 20v-9.77H5.23V20zm1 0h6.27v-9.77H12.5zM20 9.23V6.809h-7.5V9.23z");
}

</style>
