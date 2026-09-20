<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsbigw3ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:6-ft-apart-outline-sharp" /></template>
<style>
.lsbigw3ts {
  fill: currentColor;
  d: path("M7.116 21.885v-3.77h2.769v.77h-2v.73h2v2.27zm4.5 0v-3.77h2.269v.77h-1.5v.73h1v.77h-1v1.5zm4 0v-3h-1v-.77h2.769v.77h-1v3zm-7.731-.77h1.23v-.73h-1.23zM5.5 16.366l-2.558-2.557L5.5 11.25l.627.627l-1.43 1.43h14.601l-1.425-1.43l.627-.627l2.558 2.558l-2.558 2.558l-.627-.627l1.43-1.431h-14.6l1.425 1.43zM3 9.5v-.133q0-.465.248-.802q.248-.336.67-.528q.592-.256 1.24-.397q.65-.14 1.342-.14t1.341.14t1.242.397q.42.192.669.528q.248.337.248.802V9.5zm11 0v-.133q0-.465.248-.802q.248-.336.67-.528q.592-.256 1.24-.397q.65-.14 1.342-.14t1.341.14t1.242.397q.42.192.669.528q.248.337.248.802V9.5zM5.434 5.451Q5 5.017 5 4.385t.434-1.067T6.5 2.884t1.066.434T8 4.385T7.566 5.45q-.433.434-1.066.434T5.434 5.45m11 0Q16 5.017 16 4.385t.434-1.067t1.066-.434t1.066.434T19 4.385t-.434 1.066q-.433.434-1.066.434t-1.066-.434");
}

</style>
