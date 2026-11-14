<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ivl6fzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boonie-hat" /></template>
<style>
.j4ivl6fzf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 13.295V11q0-2.589 1.831-4.419Q9.411 4.75 12 4.75t4.419 1.831T18.25 11v2.295q3.475.439 3.995 5.122q.009.074.002.147q-.006.074-.027.145t-.054.136q-.034.066-.08.124t-.103.105t-.121.083t-.135.058t-.144.03t-.147.002t-.145-.027t-.136-.054q-.066-.034-.124-.08t-.105-.103t-.083-.121t-.058-.135t-.03-.144q-.426-3.833-3.255-3.833h-11q-2.829 0-3.255 3.833q-.008.073-.03.144t-.058.135t-.083.121t-.105.103t-.124.08q-.065.034-.136.054q-.071.021-.145.027q-.073.007-.147-.002q-.148-.016-.279-.088q-.13-.072-.224-.188q-.093-.117-.134-.26t-.025-.292q.52-4.683 3.995-5.122m10.946-3.045q-.219-1.491-1.337-2.609Q13.968 6.25 12 6.25T8.641 7.641Q7.523 8.759 7.304 10.25zm-9.446 1.5v1.5h9.5v-1.5z");
}

</style>
