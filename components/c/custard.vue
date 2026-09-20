<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="i4qj-1j5o"/><ellipse class="qqe97w79j"/><path class="b_xvsb4qm"/><ellipse class="uh8pepjoo"/><path class="nqcjhsblq"/><path class="s9eirobff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:custard" /></template>
<style>
.b_xvsb4qm {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M31 20c0 3.988-5.82 7.223-13 7.223S5 23.988 5 20s5.82-7.222 13-7.222S31 16.012 31 20");
}

.i4qj-1j5o {
  cx: 18px;
  cy: 23px;
  fill: var(--svg-color--939598, #939598);
  rx: 18px;
  ry: 10px;
}

.nqcjhsblq {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M18 7c3.383 0 4.724 2 5.921 2c1.691 0 2.537 2 4.229 9c.697 2.885-4.229 6-10.149 6S7.155 20.885 7.852 18c1.692-7 2.538-9 4.229-9C13.275 9 14.617 7 18 7");
}

.qqe97w79j {
  cx: 18px;
  cy: 21px;
  fill: var(--svg-color--f1f2f2, #f1f2f2);
  rx: 18px;
  ry: 10px;
}

.s9eirobff {
  fill: var(--svg-color--662113, #662113);
  d: path("M25.612 11c0 2.209-3.408 4-7.612 4s-7.612-1.791-7.612-4S13.796 7 18 7s7.612 1.791 7.612 4");
}

.uh8pepjoo {
  cx: 18px;
  cy: 20px;
  fill: var(--svg-color--8a4b38, #8a4b38);
  rx: 11px;
  ry: 5.556px;
}

</style>
