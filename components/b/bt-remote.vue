<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="zu5xrwbpn"/><circle class="y1so41beg"/><path class="jfy_z-ngt"/><path class="co4p-lp3e"/></g><path class="ho1g9c5ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bt-remote" /></template>
<style>
.co4p-lp3e {
  d: path("M14.775 25.984h-3.327a2.42 2.42 0 0 1-2.426-2.416V6.926A2.42 2.42 0 0 1 11.448 4.5h25.105a2.42 2.42 0 0 1 2.425 2.427v16.631a2.42 2.42 0 0 1-2.425 2.426h-3.33");
}

.ho1g9c5ib {
  fill: currentColor;
  d: path("M21.565 21.538a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.185 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.185 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m-6.37 3.216a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.185 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.185 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m-6.37 3.216a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.185 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m3.185 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.jfy_z-ngt {
  d: path("M16.73 13.875a10.16 10.16 0 0 1 7.317-2.946h0a10.16 10.16 0 0 1 7.343 2.881m-12.022 1.594a6.693 6.693 0 0 1 9.409-.032");
}

.y1so41beg {
  cx: 24.051px;
  cy: 37.068px;
  r: 3.161px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zu5xrwbpn {
  d: path("m29.827 18.18l-11.654.047c-.477.002-.86.584-.857 1.3l.09 22.68c.004.717.392 1.295.869 1.293l11.654-.047c.477-.001.86-.583.859-1.3h0l-.092-22.68c-.002-.716-.392-1.294-.868-1.293");
}

</style>
