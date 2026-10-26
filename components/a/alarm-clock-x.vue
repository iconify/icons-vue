<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqc5bobjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alarm-clock-x" /></template>
<style>
.zqc5bobjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5C16.4183 5 20 8.5817 20 13C20 17.4183 16.4183 21 12 21C7.5817 21 4 17.4183 4 13C4 8.5817 7.5817 5 12 5ZM9.1716 10.1716L14.8284 15.8284M14.8284 10.1716L9.1716 15.8284M3 5.0627C4.1606 3.7467 5.5957 2.7013 7.2042 2M21 5.0627C19.8394 3.7467 18.4043 2.7013 16.7958 2M8 19.9282L6.8038 22M16 19.9282L17.1962 22");
}

</style>
