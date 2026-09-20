<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":243};
const content = `<path class="hfq9yibtl"/><path class="bmh8lky-a"/><path class="bc297-q3b"/><path class="mgrmhgtda"/><path class="f91flfn2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:highcharts" /></template>
<style>
.bc297-q3b {
  fill: var(--svg-color--8087e8, #8087e8);
  d: path("m157.1.3l-42.3 98.6l63.8 20.8l.3-.8L157.5 1.2z");
}

.bmh8lky-a {
  fill: var(--svg-color--a3edba, #a3edba);
  d: path("m59.3 228.5l55.5-129.6L.8 61.7z");
}

.f91flfn2k {
  fill: var(--svg-color--6699a1, #6699a1);
  d: path("m188.4 174l12.5 69.4l55.8-98.3zM157.1.3l21.5 119.4l78.1 25.4z");
}

.hfq9yibtl {
  fill: var(--svg-color--78758c, #78758c);
  d: path("m178.6 119.7l-1.8-3.1l-60.3-19.7l-1.7 2l-2.6.6l-53.6 125.2l.7 3.8L188.4 174l1.1-2.2l-9-50z");
}

.mgrmhgtda {
  fill: var(--svg-color--30426b, #30426b);
  d: path("m178.6 119.7l9.8 54.3l4.5-.1l61.1-26.5l2.7-2.3l-3.2-2.7l-71.9-24.2z");
}

</style>
