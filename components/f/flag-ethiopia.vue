<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="de5pvs5nf"/><path class="v9cx7tb3t"/><path class="emzagpb8f"/><circle class="i7m1g5qzh"/><g class="kmgx9ub3v"><path class="r2viflb1x"/><path class="jzechubfh"/><path class="drk6mn3zd"/><path class="z4tvj6nyz"/><path class="jwb3a15vf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-ethiopia" /></template>
<style>
.de5pvs5nf {
  fill: var(--svg-color--fcdd0a, #fcdd0a);
  d: path("M0 13h36v10H0z");
}

.drk6mn3zd {
  d: path("m25.382 15.64l-4.519 3.372l1.012 3.222l-.935-.677l-1.463-4.633l.693.058l.395 1.272l3.7-2.647z");
}

.emzagpb8f {
  fill: var(--svg-color--da1219, #da1219);
  d: path("M4 31h28a4 4 0 0 0 4-4v-4H0v4a4 4 0 0 0 4 4");
}

.i7m1g5qzh {
  cx: 18px;
  cy: 18px;
  r: 9px;
  fill: var(--svg-color--0f47af, #0f47af);
}

.jwb3a15vf {
  d: path("m22.473 11.453l.337.245l-2.177 3.021l-.337-.244zm-9.359.245l.337-.245l2.174 3.021l-.336.245zm-2.637 8.923l-.129-.396l3.454-1.155l.129.397z");
}

.jzechubfh {
  d: path("m22.609 24.469l-4.73-3.345l-2.723 1.97l.357-1.1l3.964-2.824l.158.676l-1.128.759l3.739 2.759z");
}

.kmgx9ub3v {
  fill: var(--svg-color--fcdd0a, #fcdd0a);
}

.r2viflb1x {
  d: path("m13.25 24.469l1.719-5.531l-2.731-1.985h1.156l3.778 2.893l-.594.359l-.922-.83l-1.468 4.406z");
}

.v9cx7tb3t {
  fill: var(--svg-color--088930, #088930);
  d: path("M32 5H4a4 4 0 0 0-4 4v4h36V9a4 4 0 0 0-4-4");
}

.z4tvj6nyz {
  d: path("m17.872 10.07l1.86 5.487l3.344.05l-.933.68l-4.549-.038l.271-.642l.979-.06l-1.327-4.37zm-7.669 5.477h5.906l1.063-3.254l.358 1.098L16.012 18l-.526-.456l.476-1.372l-4.783.029zm7.526 6.765h.417v3.647h-.417zm7.847-2.087l-.128.396L22 19.466l.128-.396z");
}

</style>
