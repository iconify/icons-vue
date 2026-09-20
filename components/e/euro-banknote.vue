<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dpj5_xbbv"/><path class="yvrtfkr2w"/><circle class="gkpgb-bjv"/><path class="hz909ebfn"/><path class="dda_ai0uw"/><path class="rfa2p5b0x"/><path class="dlv8ambys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:euro-banknote" /></template>
<style>
.dda_ai0uw {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M14 6h8v24.062h-8z");
}

.dlv8ambys {
  fill: var(--svg-color--2a6797, #2a6797);
  d: path("M12.764 21.84c0 .658-1.474 1.447-3.301 1.447c-2.42 0-3.877-1.681-4.361-3.742H3.808a.57.57 0 1 1 0-1.139h1.129c-.008-.136-.029-.27-.029-.406c0-.3.026-.597.063-.89H3.808a.57.57 0 1 1 0-1.14h1.416c.593-1.835 2.03-3.257 4.313-3.257c1.84 0 3.008.993 3.008 1.519c0 .336-.205.612-.526.612c-.584 0-.876-1.022-2.482-1.022c-1.51 0-2.428.942-2.891 2.147h3.327a.57.57 0 1 1 0 1.14H6.351a6 6 0 0 0-.072.891c0 .134.016.27.025.405h3.668a.57.57 0 1 1 0 1.139H6.485c.389 1.43 1.346 2.631 2.978 2.631c1.563 0 2.25-.934 2.79-.934c.307.001.511.235.511.599");
}

.dpj5_xbbv {
  fill: var(--svg-color--2a6797, #2a6797);
  d: path("M2 11c-2 0-2 2-2 2v21s0 2 2 2h32c2 0 2-2 2-2V13s0-2-2-2z");
}

.gkpgb-bjv {
  cx: 25px;
  cy: 18px;
  r: 6.5px;
  fill: var(--svg-color--4289c1, #4289c1);
}

.hz909ebfn {
  fill: var(--svg-color--2a6797, #2a6797);
  d: path("M33 28.5H3c-.827 0-1.5-.673-1.5-1.5V9c0-.827.673-1.5 1.5-1.5h30c.827 0 1.5.673 1.5 1.5v18c0 .827-.673 1.5-1.5 1.5M3 8.5a.5.5 0 0 0-.5.5v18c0 .275.225.5.5.5h30c.275 0 .5-.225.5-.5V9a.5.5 0 0 0-.5-.5z");
}

.rfa2p5b0x {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M14 30h8v6h-8z");
}

.yvrtfkr2w {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M2 6C0 6 0 8 0 8v20s0 2 2 2h32c2 0 2-2 2-2V8s0-2-2-2z");
}

</style>
