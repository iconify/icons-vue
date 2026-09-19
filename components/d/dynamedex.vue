<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xu31gjbdw"/><path class="ltzswbc5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dynamedex" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ltzswbc5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.465 17.698v2.687c0 .9-.73 1.629-1.629 1.629h0c-.9 0-1.628-.73-1.628-1.629v-2.687m13.857 2.687c0 .9-.729 1.629-1.628 1.629h0c-.9 0-1.629-.73-1.629-1.629v-1.058c0-.9.73-1.629 1.629-1.629h0c.899 0 1.628.73 1.628 1.629m0 2.687v-4.316M11.246 32.493v-6.016l3.012 6.023l3.011-6.014V32.5m4.693-.76c-.26.454-.749.76-1.309.76h0a1.506 1.506 0 0 1-1.506-1.506v-.979c0-.831.675-1.505 1.506-1.505h0c.832 0 1.506.674 1.506 1.505v.49h-3.012m7.902-.49c0-.831-.675-1.505-1.506-1.505h0c-.832 0-1.506.674-1.506 1.505v.98c0 .83.674 1.505 1.506 1.505h0c.831 0 1.506-.674 1.506-1.506m0 1.506v-6.023m4.836 5.263c-.26.454-.749.76-1.309.76h0a1.506 1.506 0 0 1-1.506-1.506v-.979c0-.831.674-1.505 1.506-1.505h0c.832 0 1.506.674 1.506 1.505v.49H29.07m7.684-1.995l-3.012 3.99m3.012 0l-3.012-3.99");
}

.xu31gjbdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.935 22.014V15.5H15.4a2.85 2.85 0 0 1 2.85 2.85v.814a2.85 2.85 0 0 1-2.85 2.85zm14.83 0v-2.687c0-.9-.73-1.629-1.629-1.629h0c-.899 0-1.628.73-1.628 1.629m0 2.687v-4.316m-2.043 2.687v2.199c0 .9-.73 1.628-1.629 1.628h0a1.62 1.62 0 0 1-1.151-.477");
}

</style>
