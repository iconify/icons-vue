<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmolkvb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fishing-spot" /></template>
<style>
.xmolkvb_t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.5q0 5.842 7.759 12.567q.051.044.108.078q.058.034.121.058q.063.023.129.035t.133.012t.133-.012t.129-.035q.063-.024.121-.058t.108-.078Q20.25 15.342 20.25 9.5q0-3.417-2.416-5.834T12 1.25T6.166 3.666Q3.75 6.083 3.75 9.5m3.14-.436q2.438-3.414 5.933-1.171l2.367-1.076q.067-.03.139-.047t.146-.02t.146.01t.142.038t.132.065t.117.089q.054.05.097.11t.074.128q.067.148.067.31v4q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.162 0-.31-.067l-2.367-1.076Q9.328 13.35 6.89 9.936q-.034-.047-.06-.1q-.026-.052-.044-.107q-.018-.056-.027-.113q-.009-.058-.009-.116t.009-.116t.027-.113t.044-.107t.06-.1");
}

</style>
