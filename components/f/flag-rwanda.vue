<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jl8r7mbng"/><path class="ny0h11bae"/><path class="i7y9yrwve"/><path class="fj5a_voaq"/><circle class="p9j_ftkbf"/><circle class="dcc95bbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-rwanda" /></template>
<style>
.dcc95bbcz {
  cx: 26px;
  cy: 13px;
  r: 3px;
  fill: var(--svg-color--fad201, #fad201);
}

.fj5a_voaq {
  fill: var(--svg-color--fad201, #fad201);
  d: path("m26 5l.522 4.034l1.548-3.762l-.539 4.032L30 6.072l-1.565 3.755l3.221-2.484l-2.483 3.222L32.929 9l-3.234 2.469l4.033-.54l-3.762 1.548L34 13l-4.034.523l3.762 1.547l-4.033-.539L32.929 17l-3.756-1.565l2.483 3.222l-3.221-2.484L30 19.929l-2.469-3.234l.539 4.033l-1.548-3.762L26 21l-.522-4.034l-1.549 3.762l.54-4.033L22 19.929l1.565-3.756l-3.221 2.484l2.482-3.222L19.071 17l3.233-2.469l-4.032.539l3.761-1.547L18 13l4.033-.523l-3.761-1.548l4.032.54L19.071 9l3.755 1.565l-2.482-3.222l3.221 2.484L22 6.072l2.469 3.232l-.54-4.032l1.549 3.762z");
}

.i7y9yrwve {
  fill: var(--svg-color--00a1de, #00a1de);
  d: path("M32 5H4a4 4 0 0 0-4 4v12h36V9a4 4 0 0 0-4-4");
}

.jl8r7mbng {
  fill: var(--svg-color--20603d, #20603d);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.ny0h11bae {
  fill: var(--svg-color--fad201, #fad201);
  d: path("M0 19h36v7H0z");
}

.p9j_ftkbf {
  cx: 26px;
  cy: 13px;
  r: 4px;
  fill: var(--svg-color--00a1de, #00a1de);
}

</style>
