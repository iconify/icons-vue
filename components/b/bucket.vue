<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hf3udkbkt"/><path class="ut9iwjknl"/><ellipse class="w-92t5lrx"/><ellipse class="hftg9xbht"/><ellipse class="ctjxpyx2c"/><path class="a9spzn2td"/><path class="b1-rnoobm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bucket" /></template>
<style>
.a9spzn2td {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M18 26.413C8.406 26.413.602 18.489.602 8.75a1 1 0 0 1 2 0c0 8.637 6.908 15.663 15.398 15.663c8.491 0 15.398-7.026 15.398-15.663a1 1 0 1 1 2 0c0 9.739-7.804 17.663-17.398 17.663");
}

.b1-rnoobm {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M25.406 23.826C25.406 25.579 22.09 27 18 27s-7.406-1.421-7.406-3.174s2.116 0 7.406 0s7.406-1.753 7.406 0");
}

.ctjxpyx2c {
  cx: 18px;
  cy: 4.625px;
  fill: var(--svg-color--004a77, #004a77);
  rx: 15px;
  ry: 3.375px;
}

.hf3udkbkt {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("m3 9l4.786 23.182S10 35 18 35s10.214-2.818 10.214-2.818L33 9z");
}

.hftg9xbht {
  cx: 18px;
  cy: 5px;
  fill: var(--svg-color--55acee, #55acee);
  rx: 16px;
  ry: 4px;
}

.ut9iwjknl {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M2 5h32v4H2z");
}

.w-92t5lrx {
  cx: 18px;
  cy: 9.042px;
  fill: var(--svg-color--3b88c3, #3b88c3);
  rx: 16px;
  ry: 3.958px;
}

</style>
