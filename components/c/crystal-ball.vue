<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mct43fb3o"/><path class="ta82xxcyh"/><circle class="dq2_e1bus"/><circle class="bqlp2y3qc"/><circle class="egzvmfdwl"/><circle class="xvyki2ecx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:crystal-ball" /></template>
<style>
.bqlp2y3qc {
  cx: 23.266px;
  cy: 12.37px;
  r: 4.195px;
  fill: var(--svg-color--744eaa, #744eaa);
}

.dq2_e1bus {
  cx: 17.956px;
  cy: 15.488px;
  r: 15.288px;
  fill: var(--svg-color--aa8dd8, #aa8dd8);
}

.egzvmfdwl {
  cx: 14.875px;
  cy: 18.662px;
  r: 3.146px;
  fill: var(--svg-color--744eaa, #744eaa);
}

.mct43fb3o {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("m28.736 28.767l-21.458.076l-1.649 4.835a1.3 1.3 0 0 0-.073.582A2.04 2.04 0 0 0 7.573 36h20.894a2.04 2.04 0 0 0 2.017-1.74a1.26 1.26 0 0 0-.073-.582z");
}

.ta82xxcyh {
  fill: var(--svg-color--854836, #854836);
  d: path("m28.736 28.767l-.19-.556a1.46 1.46 0 0 0-1.389-1.001H8.883c-.63 0-1.19.403-1.389 1.001l-.216.632a17.03 17.03 0 0 0 10.678 3.754c4.088 0 7.837-1.438 10.78-3.83");
}

.xvyki2ecx {
  cx: 15.924px;
  cy: 5.028px;
  r: 2.098px;
  fill: var(--svg-color--744eaa, #744eaa);
}

</style>
