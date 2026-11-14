<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8zhk1ynp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:admission-letter" /></template>
<style>
.m8zhk1ynp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 7.5V17q0 2.75 2.75 2.75h13q2.75 0 2.75-2.75V7.5q0-2.75-2.75-2.75h-13q-1.139 0-1.945.805q-.805.806-.805 1.945M12 13.054l6.043-4.648q.118-.091.262-.13t.292-.02t.277.094t.22.193q.046.058.078.124q.033.067.052.138t.024.145t-.004.147t-.034.143q-.023.07-.06.134t-.086.12t-.107.1l-6.5 5q-.049.038-.103.067t-.112.049t-.12.03q-.06.01-.122.01t-.122-.01t-.12-.03q-.058-.02-.112-.049t-.103-.067l-6.5-5q-.059-.045-.107-.1q-.049-.056-.086-.12t-.06-.134q-.024-.07-.034-.143q-.009-.073-.004-.147t.024-.145t.052-.138q.032-.066.078-.124q.045-.059.1-.107q.056-.049.12-.086t.134-.06t.143-.034q.073-.009.147-.004t.145.024t.138.052q.066.032.124.078z");
}

</style>
