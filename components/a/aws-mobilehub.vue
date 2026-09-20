<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":280};
const content = `<defs><linearGradient x1="-2.587%" y1="59.832%" x2="97.695%" y2="41.181%" id="ssvg-id-aws-mobilehuba"><stop offset="0%" class="g6eb35krk"/><stop offset="35.63%" class="fz1xezbad"/><stop offset="45.19%" class="ox85kj3ny"/><stop offset="61.16%" class="lr870rban"/><stop offset="81.44%" class="k4m3ew_uw"/><stop offset="100%" class="gvuqp6bfq"/></linearGradient></defs><path class="urzz-v1ky"/><path class="vq7lz4eqh"/><path class="jo1lw7tnl"/><path fill="url(#ssvg-id-aws-mobilehuba)" class="v06i7qm-j"/><path class="mypod93br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:aws-mobilehub" /></template>
<style>
.fz1xezbad {
  stop-color: var(--svg-color--d64626, #D64626);
  stop-opacity: 0.96;
}

.g6eb35krk {
  stop-color: var(--svg-color--f7962f, #F7962F);
  stop-opacity: 0.96;
}

.gvuqp6bfq {
  stop-color: var(--svg-color--87509f, #87509F);
}

.jo1lw7tnl {
  d: path("M145.842 250.265l46.803-26.138l15.646 8.988l18.23-10.085l.388-21.333l-18.23-10.86l-18.618 10.472v15.375l-49.592 27.696l-12.857-7.386l-16.686 9.586l-44.933-26.556l.334-18.715l-18.23-10.473l-18.618 10.473v21.333l18.23 10.473l13.01-7.197l48.663 28.76V268.8l18.23 10.473l18.23-10.473v-18.535z");
  fill: var(--svg-color--df5343, #DF5343);
}

.k4m3ew_uw {
  stop-color: var(--svg-color--a44c73, #A44C73);
  stop-opacity: 0.989;
}

.lr870rban {
  stop-color: var(--svg-color--bf4949, #BF4949);
  stop-opacity: 0.976;
}

.mypod93br {
  d: path("M127.224 185.794l-46.933-27.152l.388-54.69L128 77.188l46.545 27.54l-.775 54.69l-46.546 26.376zm-42.279-29.867l42.28 24.437l41.502-23.661l.776-49.26l-41.89-24.437l-42.28 23.66l-.388 49.261z");
  fill: var(--svg-color--fff, #FFF);
}

.ox85kj3ny {
  stop-color: var(--svg-color--d04730, #D04730);
  stop-opacity: 0.966;
}

.urzz-v1ky {
  d: path("M170.422 31.57l46.79 26.778v20.004l11.636 6.283v59.19l-11.636 6.284v21.333l19.394 10.473L256 171.055v-20.946l-19.394-10.473V88.824L256 77.964V57.406l-19.394-10.86l-12.554 6.779l-53.385-30.553V10.861L153.212 0l-17.454 10.473v21.333l17.454 10.473l17.21-10.709z");
  fill: var(--svg-color--ad688a, #AD688A);
}

.v06i7qm-j {
  d: path("M58.57 91.152v80.678l69.042 39.564l67.879-38.4l1.164-80.679L128 51.975L58.57 91.153z");
}

.vq7lz4eqh {
  d: path("M23.273 86.73v55l15.515 8.38v21.332l-19.394 10.473L0 171.055v-20.946l11.636-6.284V84.48L0 77.964V57.406l19.394-10.86l13.102 7.074l45.08-25.799v-16.96L96.97 0l19.394 10.473v21.333L96.97 42.28l-14.677-8.22l-43.505 24.899v19.394L23.273 86.73z");
  fill: var(--svg-color--f58435, #F58435);
}

</style>
