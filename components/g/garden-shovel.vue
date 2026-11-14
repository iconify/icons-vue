<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqj5c5bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:garden-shovel" /></template>
<style>
.yqj5c5bgg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.97 6.97l2.5-2.5q.024-.024.05-.046q3.305-2.754 7.186-1.645q.092.026.174.075q.083.048.15.116q.068.067.116.15q.049.082.075.174q1.109 3.881-1.645 7.186q-.022.026-.046.05l-2.5 2.5q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163L14 11.061L8.53 16.53q-.105.106-.243.163T8 16.75t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 16q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113L12.939 10L10.97 8.03q-.106-.105-.163-.243T10.75 7.5t.057-.287t.163-.243m-5.833 9.194l.001-.001q1.251-.417 2.184.515q.932.933.515 2.184l-.107.322q-.397 1.19-1.618 1.479t-2.108-.599l-.068-.068q-.888-.887-.599-2.108t1.479-1.618z");
}

</style>
