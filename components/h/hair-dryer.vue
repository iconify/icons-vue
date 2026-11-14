<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uue-boa8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hair-dryer" /></template>
<style>
.uue-boa8c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.353 5.765l7.228-1.446q1.492-1.817 3.876-2.043q2.531-.24 4.412 1.47Q20.75 5.457 20.75 8t-1.881 4.254q-.078.07-.157.138L18 19.042q-.021 2.708-2.75 2.708h-.5q-2.729 0-2.75-2.708l-.71-6.631q-.377-.325-.709-.73l-7.228-1.446q-.063-.012-.124-.036q-.06-.023-.115-.056t-.104-.075t-.09-.093q-.041-.049-.073-.106t-.053-.117t-.033-.124T2.75 9.5v-3q0-.065.011-.128q.011-.064.033-.124q.022-.061.053-.117q.032-.057.073-.106q.041-.05.09-.093t.104-.075q.055-.033.115-.056q.061-.024.124-.036M12.25 8q0 2.75 2.75 2.75T17.75 8T15 5.25T12.25 8m.651 5.373l.595 5.547q.004.04.004.08q0 1.25 1.25 1.25h.5q1.25 0 1.25-1.25q0-.04.004-.08l.594-5.543q-1.218.482-2.641.347q-.832-.079-1.556-.351");
}

</style>
