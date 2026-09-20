<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dpewt9zza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-16-regular" /></template>
<style>
.dpewt9zza {
  fill: currentColor;
  d: path("M8.538 1.019A7.002 7.002 0 0 1 8 15A7 7 0 0 1 3.153 2.948a.501.501 0 0 1 .694.721a6 6 0 1 0 4.615-1.652a.5.5 0 0 1 .076-.998m-4.202 4.18c-.268-.539.326-1.133.865-.865l.114.07l2.242 1.699c.37.283.71.546.97.75c.245.192.456.36.536.44A1.25 1.25 0 0 1 7.295 9.06c-.08-.08-.249-.29-.44-.535c-.205-.26-.467-.6-.75-.97a421 421 0 0 1-1.698-2.242z");
}

</style>
