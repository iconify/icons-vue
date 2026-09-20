<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="sws-_2nni"/><path class="sugjxub-l"/><ellipse class="z1u41db5i"/><path class="zzfo26bee"/><ellipse class="t3s_k76cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:loudspeaker" /></template>
<style>
.sugjxub-l {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M35.825 14.75c0 6.902-1.544 12.5-3.45 12.5c-1.905 0-20.45-5.598-20.45-12.5s18.545-12.5 20.45-12.5c1.906 0 3.45 5.597 3.45 12.5");
}

.sws-_2nni {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M12.908 30.75c-.276 2.209-2.291 3-4.5 3s-3.776-1.791-3.5-4l1-9c.276-2.209 2.291-4 4.5-4s6.468 0 3.5 4s-1 10-1 10");
}

.t3s_k76cn {
  cx: 31.325px;
  cy: 14.75px;
  fill: var(--svg-color--99aab5, #99aab5);
  rx: 1.5px;
  ry: 4.348px;
}

.z1u41db5i {
  cx: 32.375px;
  cy: 14.75px;
  fill: var(--svg-color--66757f, #66757f);
  rx: 3.45px;
  ry: 12.5px;
}

.zzfo26bee {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("m17.925 21.75l-14-1c-5 0-5-12 0-12l14-1c-3 3-3 11 0 14");
}

</style>
