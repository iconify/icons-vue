<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v1kbweb6z"/><path class="g49bi7yqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:electrical-plan" /></template>
<style>
.g49bi7yqe {
  d: path("m17.982 15.209l-2.016 2.394a.698.698 0 0 0 .534 1.147a1.108 1.108 0 0 1 1.059 1.434l-.059.191a.324.324 0 0 0 .562.297l2.001-2.501A.721.721 0 0 0 19.5 17a1.08 1.08 0 0 1-1.026-1.423l.026-.077a.303.303 0 0 0-.518-.291");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v1kbweb6z {
  d: path("M14.6 21H4.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q3 19.336 3 19.25V4.75q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026T4.75 3h14.5q.086 0 .172.008t.169.026q.085.016.167.041t.162.058t.155.074t.147.088t.138.102t.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167q.017.084.026.169T21 4.75v9.125M12 3v6m0 4v8m-9-9h5");
}

</style>
