<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVG6xxPjdBv" cx="-347.632" cy="388.446" r="1" gradientTransform="matrix(3.568 0 0 -3.757 1255.663 1473.926)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o6w3112lr"/><stop offset=".22" class="b7cfr6bzo"/><stop offset=".44" class="nw2eyhv7q"/><stop offset=".65" class="b9_muhbgx"/><stop offset=".86" class="jl1al0b3h"/><stop offset="1" class="mfsg-tbww"/></radialGradient></defs><path class="u-pq-yb0g"/><path class="ko01xobhf"/><path class="kqv8vyb1t"/><path class="fy165kbss"/><path class="rb5d_bctp"/><path class="a2epbobhy"/><path class="me14ycb2h"/><path class="nn-d_9bno"/><path class="ylyj-4pzl"/><path class="gk5oidchi"/><path fill="url(#SVG6xxPjdBv)" class="g8mfmmb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-lilypond" /></template>
<style>
.a2epbobhy {
  fill: var(--svg-color--c8e5da, #c8e5da);
  d: path("M14.005 24.144c2.724-1.292 5.424-4.711 5.424-4.711s5.853-1.98 7.477-4.142a18.2 18.2 0 0 0-7.467-5.044s-.164-5.356-1.777-7.335c-1.737 1.281-4.351 6.84-4.351 6.84S7.283 8.691 5.2 9.473c1.371 3.958 5.619 7.336 5.619 7.336a55 55 0 0 0 3.186 7.335");
}

.b7cfr6bzo {
  stop-color: var(--svg-color--ffa117, #ffa117);
}

.b9_muhbgx {
  stop-color: var(--svg-color--ffc00e, #ffc00e);
}

.fy165kbss {
  fill: var(--svg-color--94a39d, #94a39d);
  d: path("M5.485 21.5c.758-2.949 4.843-7.2 4.843-7.2S8.183 6.8 9.239 4.932c2.233-.164 8.055 5.205 8.055 5.205s6.476-2.409 9.172-1.484c-.266 2.818-4.166 4.886-4.166 4.886s.92 8.425-.347 11.079c-2.145.409-6.783-4.625-6.783-4.625S7.652 24.144 5.485 21.5");
}

.g8mfmmb3b {
  d: path("M15.29 18.221a3.666 3.666 0 0 0 3.568-3.757a3.666 3.666 0 0 0-3.568-3.757a3.666 3.666 0 0 0-3.568 3.757a3.666 3.666 0 0 0 3.568 3.757");
}

.gk5oidchi {
  fill: var(--svg-color--f8ece7, #f8ece7);
  d: path("m19.509 21.813l.152-15.544a.15.15 0 0 0-.018-.072a.14.14 0 0 0-.051-.053a.13.13 0 0 0-.137 0L6.178 14.89a.8.8 0 0 0-.27.31a.83.83 0 0 0 .049.809a.76.76 0 0 0 .306.271l12.488 6.038a.51.51 0 0 0 .509-.036a.55.55 0 0 0 .181-.2a.6.6 0 0 0 .068-.268Z");
}

.jl1al0b3h {
  stop-color: var(--svg-color--ffdb06, #ffdb06);
}

.ko01xobhf {
  fill: var(--svg-color--80b48e, #80b48e);
  d: path("M15.877 29.113c7.664 0 13.877-4.507 13.877-10.067S23.542 8.979 15.877 8.979S2 13.486 2 19.046s6.213 10.067 13.877 10.067");
}

.kqv8vyb1t {
  d: path("M5.235 21.858c.781-3.041 4.994-7.422 4.994-7.422S8.017 6.7 9.106 4.775c2.3-.169 8.349 6.167 8.349 6.167s6.636-3.283 9.417-2.33c-.28 2.9-4.3 5.036-4.3 5.036s.949 8.688-.358 11.425c-2.212.421-6.994-4.768-6.994-4.768s-7.75 4.28-9.985 1.553");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.me14ycb2h {
  d: path("M22.721 15.37c-.662-2.356-4.109-4.738-4.109-4.738S15.6 5.6 13.226 5.039C10.405 9.564 11.8 17.61 11.8 17.61s7.951 1.007 10.921-2.24");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.mfsg-tbww {
  stop-color: var(--svg-color--fff100, #fff100);
}

.nn-d_9bno {
  fill: var(--svg-color--efe7e4, #efe7e4);
  d: path("M22.4 15.195c-.633-2.259-3.942-4.539-3.942-4.539S15.571 5.837 13.29 5.3c-2.717 4.345-1.39 12.061-1.39 12.061s7.643.953 10.5-2.166");
}

.nw2eyhv7q {
  stop-color: var(--svg-color--ffac14, #ffac14);
}

.o6w3112lr {
  stop-color: var(--svg-color--ff9d18, #ff9d18);
}

.rb5d_bctp {
  d: path("M14.028 24.556c2.83-1.342 5.634-4.8 5.634-4.8s6.081-2.148 7.769-4.4a20.46 20.46 0 0 0-7.77-5.386S19.5 4.556 17.826 2.5c-1.8 1.33-4.52 7.106-4.52 7.106S7.045 8.5 4.881 9.315c1.422 4.112 5.836 7.621 5.836 7.621a57 57 0 0 0 3.311 7.62");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.u-pq-yb0g {
  d: path("M16 29.5c7.732 0 14-4.507 14-10.067S23.732 9.366 16 9.366S2 13.873 2 19.433S8.268 29.5 16 29.5");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.ylyj-4pzl {
  d: path("m19.831 22.081l.158-16.1a.15.15 0 0 0-.019-.075a.14.14 0 0 0-.052-.055a.13.13 0 0 0-.142 0l-13.75 9.063a.8.8 0 0 0-.28.321a.86.86 0 0 0 .051.839a.8.8 0 0 0 .317.281l12.932 6.252a.53.53 0 0 0 .269.052a.54.54 0 0 0 .26-.09a.6.6 0 0 0 .187-.209a.6.6 0 0 0 .069-.278Z");
  opacity: var(--svg-opacity--0-75, 0.75);
}

</style>
