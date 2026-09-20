<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zphf-w9pm"/><path class="v2asvcbpf"/><path class="nbyup-blt"/><circle class="oqt63nbht"/><path class="a3xvyrmhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cricket-game" /></template>
<style>
.a3xvyrmhy {
  fill: var(--svg-color--662113, #662113);
  d: path("M19 36a1 1 0 0 1-1-1v-8a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1");
}

.nbyup-blt {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M.983 4.528L4.528.984L9.844 6.3L6.3 9.844z");
}

.oqt63nbht {
  cx: 19px;
  cy: 31px;
  r: 5px;
  fill: var(--svg-color--be1931, #be1931);
}

.v2asvcbpf {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M13.388 9.844c.979.979 4.522 6.109 3.544 7.088c-.979.978-6.109-2.565-7.088-3.544l-8.86-8.86A2.507 2.507 0 0 1 4.528.984z");
}

.zphf-w9pm {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M35.538 26.679s1.328 2.214-2.658 6.201c-3.987 3.986-6.201 2.658-6.201 2.658L7.185 16.046s.977-2.748 3.544-5.316s5.316-3.544 5.316-3.544z");
}

</style>
