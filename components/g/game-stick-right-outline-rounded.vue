<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbemwmakn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-stick-right-outline-rounded" /></template>
<style>
.hbemwmakn {
  fill: currentColor;
  d: path("M17.675 13.06Q20 11.86 20 10.137T17.675 7.2T12 5.984T6.325 7.2T4 10.136t2.325 2.924T12 14.262t5.675-1.2m-1.406 1.597v2.727q0 .666-.474 1.14T14.654 19H9.327q-.667 0-1.141-.475t-.475-1.14v-2.727q-2.12-.666-3.416-1.851T3 10.133Q3 7.99 5.62 6.486t6.376-1.505t6.38 1.505T21 10.133q0 1.488-1.295 2.674t-3.436 1.85m-5.244-2.007q.112-.115.112-.27v-1.626h.911l1.13 1.83q.05.082.133.132t.185.05q.23 0 .335-.199q.106-.198-.037-.384l-1.04-1.637q.5-.194.762-.53t.263-.843q0-.73-.468-1.127q-.469-.396-1.378-.396h-1.164q-.16 0-.281.121q-.12.121-.12.283v4.327q0 .154.11.269q.113.116.274.116t.273-.116m.112-2.57V8.372h.717q.573 0 .852.213t.279.625q0 .439-.27.656q-.269.216-.848.216z");
}

</style>
