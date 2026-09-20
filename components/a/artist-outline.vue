<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu6nhcbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:artist-outline" /></template>
<style>
.qu6nhcbkt {
  fill: currentColor;
  d: path("M18.616 9.846H21.5v1.539h-2v5.23q0 .84-.58 1.42t-1.419.58t-1.42-.58t-.581-1.419t.58-1.42t1.42-.58q.316 0 .594.094q.279.096.521.298zM3.5 18.616v-1.647q0-.625.36-1.161q.361-.537.97-.835q1.455-.698 2.853-1.028t2.817-.33q.858 0 1.626.105t1.51.334q-.172.204-.313.408q-.14.204-.248.415q-.573-.13-1.249-.196q-.676-.065-1.326-.065q-1.329 0-2.627.311q-1.298.312-2.565.923q-.38.183-.593.485q-.215.302-.215.634v.647h8.352q.05.269.13.512q.079.244.216.488zm4.877-8.108Q7.5 9.63 7.5 8.385t.877-2.123t2.123-.877t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877m3.535-.711q.588-.587.588-1.412t-.588-1.413t-1.412-.587t-1.413.587T8.5 8.385t.587 1.412t1.413.588t1.412-.588M10.5 17.616");
}

</style>
