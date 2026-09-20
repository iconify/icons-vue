<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bqldpcbee"/><path class="ts_mc9byl"/><path class="wxo5aqb_n"/><path class="mfaj2pbwr"/><path class="vbt3k18gf"/><path class="qr22_6bfm"/><path class="z7xiygbna"/><g class="ma1kvlm8s"><ellipse class="kied71bqt"/><path class="dr16y_lze"/></g><ellipse class="rb80xxbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:ice-hockey" /></template>
<style>
.bqldpcbee {
  fill: var(--svg-color--a1887f, #a1887f);
  d: path("M120.83 6.94c-1.96-.9-4.52-2.24-5.42-.28l-.45.97c-.9 1.96 2.37 5.15 4.33 6.05s4.3.03 5.2-1.93l.45-.97c.91-1.96-2.14-2.94-4.11-3.84");
}

.dr16y_lze {
  d: path("M3.29 115.86h26.83v6.41H3.29z");
}

.kied71bqt {
  cx: 16.78px;
  cy: 122.05px;
  rx: 13.42px;
  ry: 1.41px;
}

.ma1kvlm8s {
  fill: var(--svg-color--5d4137, #5d4137);
}

.mfaj2pbwr {
  fill: var(--svg-color--5d4137, #5d4137);
  d: path("M78.66 101.12c-2.53 6.84-9.66 6.98-12.93 7.49c-.02 0-.04.01-.07.01l1.07 12.08c13.77-1.45 16.84-7.94 19.08-13.31c1.86-4.47 6.96-18.08 6.96-18.08l-8.01-3.06z");
}

.qr22_6bfm {
  fill: var(--svg-color--c2afa8, #c2afa8);
  d: path("M111.11 20.93L84.75 86.25l8.02 3.06l25.24-65.55z");
}

.rb80xxbzu {
  cx: 16.78px;
  cy: 115.86px;
  fill: var(--svg-color--8d6e63, #8d6e63);
  rx: 13.42px;
  ry: 1.41px;
}

.ts_mc9byl {
  fill: var(--svg-color--5d4137, #5d4137);
  d: path("M38.49 108.87c-3.12.3-2.96 2.46-2.96 2.46l.11 9.79c.29 3.02 3.09 2.54 3.09 2.54s1.84-.18 4.55-.44L42.75 109c-2.57-.07-4.26-.13-4.26-.13");
}

.vbt3k18gf {
  fill: var(--svg-color--a1887f, #a1887f);
  d: path("m123.27 10.1l-6.62-2.91l-5.54 13.74l6.9 2.83z");
}

.wxo5aqb_n {
  fill: var(--svg-color--f1592b, #f1592b);
  d: path("m42.75 109l.54 14.22c5.86-.57 15.78-1.53 19.98-1.94c1.22-.12 2.37-.32 3.46-.58l-1.07-12.08c-4.83.74-16.56.55-22.91.38");
}

.z7xiygbna {
  fill: var(--svg-color--a1887f, #a1887f);
  d: path("m112.39 38.35l1.31-3.39l-5-8.07l-1.34 3.32zm-4.49 11.66l1.31-3.4l-5.1-8.34l-1.34 3.31zm-4.49 11.65l1.31-3.4l-5.2-8.62l-1.34 3.32zm-4.48 11.66l1.31-3.4l-5.31-8.91l-1.33 3.32zm-4.49 11.65l1.31-3.4l-5.4-9.18l-1.34 3.32z");
}

</style>
