<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="fvtbvcpow"/><path class="b3phpnb5q"/><ellipse class="ywdb3zisg"/><path class="irgn3sudc"/><path class="y43by3b8s"/><ellipse class="g9juf2bsf"/><ellipse class="mq7-6hbim"/><path class="emns8pbry"/><path class="zdwbyfqmv"/><ellipse class="l24z6acxi"/><ellipse class="yxx_f5b-y"/><ellipse class="v-utjpb-c"/><path class="yxymwfb4e"/><ellipse class="c-dze-bwu"/><ellipse class="vrdkvsbpp"/><ellipse class="q_k9hkw7k"/><path class="tx3c59bgh"/><path class="j6-bkfciq"/><path class="sef1-kwgb"/><path class="qiki-bw6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:fondue" /></template>
<style>
.b3phpnb5q {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M12 31.001h24v1H12z");
}

.c-dze-bwu {
  cx: 24px;
  cy: 9.001px;
  fill: var(--svg-color--ea596e, #ea596e);
  rx: 11.969px;
  ry: 3px;
}

.emns8pbry {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M19.507 27.931c.808.336 2.508.569 4.493.569s3.685-.233 4.493-.569c-.807-.335-2.507-.569-4.493-.569s-3.685.234-4.493.569");
}

.fvtbvcpow {
  cx: 24px;
  cy: 31.93px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 12px;
  ry: 3px;
}

.g9juf2bsf {
  cx: 24px;
  cy: 27.5px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  rx: 6px;
  ry: 1.5px;
}

.irgn3sudc {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M18 31.001c0-.828 2.686-2.501 6-2.501s6 1.672 6 2.501c0 .828-2.686 1.5-6 1.5s-6-.672-6-1.5");
}

.j6-bkfciq {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M18.588 10.956a42 42 0 0 0 2.72.225L13.63 7.4a.5.5 0 0 0-.441.897z");
}

.l24z6acxi {
  cx: 24px;
  cy: 22.001px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 10px;
  ry: 2px;
}

.mq7-6hbim {
  cx: 24px;
  cy: 27.5px;
  fill: var(--svg-color--ffac33, #ffac33);
  rx: 5px;
  ry: 1px;
}

.q_k9hkw7k {
  cx: 24px;
  cy: 9.934px;
  fill: var(--svg-color--ffac33, #ffac33);
  rx: 9.975px;
  ry: 1.317px;
}

.qiki-bw6y {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M19.289 7.095a.5.5 0 0 0-.695.131a.5.5 0 0 0 .131.695l4.874 3.326q.2.003.401.004q.687-.001 1.352-.019z");
}

.sef1-kwgb {
  fill: var(--svg-color--269, #269);
  d: path("M10.334 1.589a.95.95 0 0 0 .287 1.353l8.508 5.274c.435.269.598.106.834-.056c.065-.278.158-.49-.251-.797l-8.012-6a.953.953 0 0 0-1.366.226");
}

.tx3c59bgh {
  fill: var(--svg-color--269, #269);
  d: path("M3.989 3.209a.95.95 0 0 0 .475 1.299l9.165 4.024c.468.206.607.02.817-.173c.025-.285.087-.507-.361-.753L5.308 2.793a.95.95 0 0 0-1.319.416");
}

.v-utjpb-c {
  cx: 24px;
  cy: 20.401px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 8px;
  ry: 1.4px;
}

.vrdkvsbpp {
  cx: 24px;
  cy: 9.001px;
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  rx: 10.972px;
  ry: 2.25px;
}

.y43by3b8s {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M18 27.52h12v3.481H18z");
}

.ywdb3zisg {
  cx: 24px;
  cy: 31.018px;
  fill: var(--svg-color--66757f, #66757f);
  rx: 12px;
  ry: 3px;
}

.yxx_f5b-y {
  cx: 24px;
  cy: 21.001px;
  fill: var(--svg-color--66757f, #66757f);
  rx: 10px;
  ry: 2px;
}

.yxymwfb4e {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M35.939 9.001c0-1.499-5.964-2.994-11.939-3h-.03c-5.974.005-11.939 1.5-11.939 3c0 .327-.006.668-.012 1.014c-.036.799-1.103.444-1.994.289l-.019.001c-.035-.007-.067-.022-.103-.027L2.47 9.08C1.383 8.905.365 9.812.208 11.097l-.143 1.168c-.157 1.284.611 2.413 1.708 2.508l7.5.649c.075.007.148-.003.223-.003c.021.003.038.012.06.013c1.298.099 2.721.058 3.136.919a1 1 0 0 0 .098.164a6.24 6.24 0 0 0 2.131 2.66c1.764 1.264 4.654 1.823 9.05 1.826h.03c4.396-.003 7.286-.562 9.05-1.826c3.425-2.456 2.888-6.876 2.888-10.174");
}

.zdwbyfqmv {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M14 21.001c-.376.827-.839 9.111-.839 9.762s.434.521 2.257.477c.738-.018.608-.651.738-3.993c.056-1.437.304-4.297.521-5.078c.216-.781-2.185-2.25-2.677-1.168m19.993 0c.376.827.839 9.111.839 9.762s-.434.521-2.257.477c-.738-.018-.608-.651-.738-3.993c-.056-1.437-.304-4.297-.521-5.078s2.185-2.25 2.677-1.168M24 33.237a.675.675 0 0 1-.673-.673v-9.722c0-.37.303-.673.673-.673s.673.303.673.673v9.722c0 .37-.303.673-.673.673");
}

</style>
