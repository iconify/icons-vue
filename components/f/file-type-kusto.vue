<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect transform="rotate(-44.999 8.266 23.737)" class="xs9u8x1mk"/><rect transform="rotate(-44.999 6.301 17.78)" class="fad7rxb5o"/><rect transform="rotate(-44.999 14.162 25.7)" class="pa9gyhovu"/><path class="mb2xtkb5m"/><path class="utjigzghh"/><path class="nv9a0jbmx"/><rect transform="rotate(-44.999 17.623 10.4)" class="s0vyjjbfi"/><rect transform="rotate(-44.999 21.579 6.446)" class="yyuh960-r"/><rect transform="rotate(-44.999 21.578 14.353)" class="j4g7-5j8j"/><rect transform="rotate(-44.999 25.531 10.4)" class="z1azdqe2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-kusto" /></template>
<style>
.fad7rxb5o {
  width: 9.859px;
  height: 2.796px;
  x: 1.372px;
  y: 16.382px;
  fill: var(--svg-color--b8d432, #b8d432);
  rx: 0.439px;
}

.j4g7-5j8j {
  width: 2.796px;
  height: 2.796px;
  x: 20.18px;
  y: 12.955px;
  fill: var(--svg-color--fff, #fff);
  rx: 0.622px;
}

.mb2xtkb5m {
  fill: var(--svg-color--0078d4, #0078d4);
  d: path("M30 2H2l28 27.999z");
}

.nv9a0jbmx {
  fill: var(--svg-color--fff, #fff);
  d: path("M30 29.999V2L16 16z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pa9gyhovu {
  width: 9.859px;
  height: 2.796px;
  x: 9.232px;
  y: 24.301px;
  fill: var(--svg-color--b8d432, #b8d432);
  rx: 0.439px;
}

.s0vyjjbfi {
  width: 2.796px;
  height: 2.796px;
  x: 16.226px;
  y: 9.001px;
  fill: var(--svg-color--fff, #fff);
  rx: 0.622px;
}

.utjigzghh {
  fill: var(--svg-color--59b4d9, #59b4d9);
  d: path("m10.282 10.282l11.436 11.436L30 13.436V2H18.564z");
}

.xs9u8x1mk {
  width: 15.433px;
  height: 2.796px;
  x: 0.55px;
  y: 22.339px;
  fill: var(--svg-color--b8d432, #b8d432);
  rx: 0.439px;
}

.yyuh960-r {
  width: 2.796px;
  height: 2.796px;
  x: 20.18px;
  y: 5.048px;
  fill: var(--svg-color--fff, #fff);
  rx: 0.622px;
}

.z1azdqe2q {
  width: 2.796px;
  height: 2.796px;
  x: 24.133px;
  y: 9.002px;
  fill: var(--svg-color--fff, #fff);
  rx: 0.622px;
}

</style>
