<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zraerp12u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gamepad-right-outline-rounded" /></template>
<style>
.zraerp12u {
  fill: currentColor;
  d: path("m11.435 8.512l-1.193-1.193q-.13-.13-.186-.27T10 6.748v-2.94q0-.348.23-.578t.578-.23h2.384q.348 0 .578.23t.23.578v2.94q0 .162-.056.301t-.186.27l-1.193 1.193q-.13.13-.267.183T12 8.748t-.298-.053t-.268-.183m4.054 4.054q-.13-.131-.183-.268q-.053-.136-.053-.298t.053-.298t.183-.267l1.193-1.193q.13-.13.27-.186t.301-.056h2.94q.348 0 .578.23t.23.578v2.384q0 .349-.23.578t-.578.23h-2.94q-.161 0-.301-.056t-.27-.186zM3 13.192v-2.384q0-.348.23-.578t.578-.23h2.94q.162 0 .301.056t.27.186l1.193 1.193q.13.13.183.267t.053.298t-.053.298t-.183.268l-1.193 1.192q-.13.13-.27.186T6.748 14h-2.94q-.348 0-.578-.23T3 13.192m7 7v-2.94q0-.161.056-.301t.186-.27l1.192-1.192q.132-.131.268-.184q.137-.053.298-.053t.298.053t.268.184l1.192 1.192q.13.13.186.27t.056.301v2.94q0 .349-.23.578t-.578.23h-2.384q-.348 0-.578-.23t-.23-.578M12 7.65l1-1V4h-2v2.65zM4 13h2.65l1-1l-1-1H4zm7 7h2v-2.65l-1-1l-1 1z");
}

</style>
