<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":259};
const content = `<defs><linearGradient id="SVGU6trOdWl" x1="100.012%" x2="0%" y1="49.991%" y2="49.991%"><stop offset="0%" class="r90t2nbhc"/><stop offset="100%" class="ix7fdbb9p"/></linearGradient><linearGradient id="SVGPVyild9u" x1="100.012%" x2="0%" y1="49.998%" y2="49.998%"><stop offset="50%" class="x2p68objs"/><stop offset="100%" class="et78nxbti"/></linearGradient><linearGradient id="SVGYsPYeIBI" x1="-.018%" x2="100.023%" y1="49.998%" y2="49.998%"><stop offset="0%" class="py5pzv8vr"/><stop offset="100%" class="cfdsm9snh"/></linearGradient></defs><path class="ld07p50gc"/><path class="vmemj2asx"/><path fill="url(#SVGU6trOdWl)" class="qu6rmzbuf"/><path fill="url(#SVGPVyild9u)" class="hs-wx_m1n"/><path fill="url(#SVGYsPYeIBI)" class="dqh97-bhu"/><path class="jjtz-abcw"/><path class="i5j6wd-2d"/><path class="trdh0vbbw"/><path class="t27gdacwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:apiary" /></template>
<style>
.cfdsm9snh {
  stop-color: var(--svg-color--7cc9b8, #7cc9b8);
}

.dqh97-bhu {
  d: path("M127.693 110.601v147.392l63.847-36.867v-73.658l63.77-36.867V36.867z");
}

.et78nxbti {
  stop-color: var(--svg-color--78bbc1, #78bbc1);
}

.hs-wx_m1n {
  d: path("M127.693 110.601L0 36.867v73.734l63.847 36.867v73.658l63.846 36.867l63.847-36.867v-73.658l63.77-36.867V36.867z");
}

.i5j6wd-2d {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M127.693 258.146v-73.734l-63.846 36.867z");
  opacity: var(--svg-opacity--0-1, 0.1);
}

.ix7fdbb9p {
  stop-color: var(--svg-color--8ad3b8, #8ad3b8);
}

.jjtz-abcw {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M127.693 184.259v73.734l63.847-36.867z");
  opacity: var(--svg-opacity--0-05, 0.05);
}

.ld07p50gc {
  fill: var(--svg-color--13a049, #13a049);
  d: path("M127.693 36.867v73.58l63.847-36.866V0z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.py5pzv8vr {
  stop-color: var(--svg-color--4379a7, #4379a7);
}

.qu6rmzbuf {
  d: path("m191.54 0l-63.847 36.867L63.847 0L0 36.867l127.693 73.734L255.31 36.867z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.r90t2nbhc {
  stop-color: var(--svg-color--37bda6, #37bda6);
}

.t27gdacwn {
  fill: var(--svg-color--231f20, #231f20);
  d: path("m191.54 73.734l-63.847 36.867l63.847 36.867l63.77-36.867z");
  opacity: var(--svg-opacity--0-05, 0.05);
}

.trdh0vbbw {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M63.847 73.734L0 110.601l63.847 36.867l63.846-36.867z");
  opacity: var(--svg-opacity--0-05, 0.05);
}

.vmemj2asx {
  fill: var(--svg-color--a2cc39, #a2cc39);
  d: path("M127.693 36.867L63.847 0v73.734l63.846 36.867z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.x2p68objs {
  stop-color: var(--svg-color--4bb6ad, #4bb6ad);
}

</style>
