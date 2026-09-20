<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy0ki7wgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-r-outline-rounded" /></template>
<style>
.xy0ki7wgc {
  fill: currentColor;
  d: path("M10.454 14.97q.123-.126.123-.305v-2.042h1.175l1.433 2.294q.061.087.141.133t.191.046q.247 0 .376-.209t-.024-.418l-1.294-2.06q.623-.217.938-.645q.314-.43.314-1.058q0-.933-.575-1.377t-1.733-.445h-.99q-.348 0-.578.23t-.23.578v4.999q0 .178.126.292t.305.113t.302-.126m.123-3.103V9.706l.887-.006q.707-.006 1.092.275q.385.28.385.787q0 .53-.384.818t-1.082.287zM3 17.384V8.27q0-1.361.973-2.325q.973-.963 2.354-.963h11.346q1.38 0 2.354.963Q21 6.908 21 8.27v9.116q0 .67-.472 1.143q-.472.472-1.143.472H4.615q-.67 0-1.143-.472Q3 18.056 3 17.385M4.616 18h14.769q.269 0 .442-.173t.173-.442V8.269q0-.96-.684-1.624q-.683-.664-1.643-.664H6.327q-.96 0-1.643.664Q4 7.31 4 8.27v9.116q0 .269.173.442t.443.173m0 0H4h16z");
}

</style>
