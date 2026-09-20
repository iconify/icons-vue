<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k7csiybpv"/><path class="nl8s30bhe"/><path class="pitsp82dj"/><path class="lvo_2zbtq"/><rect class="xp5fiybkn"/><path class="thbvurb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:g-web-browser" /></template>
<style>
.k7csiybpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.324 5.5c5.205 2.259 6.978 12.41 4.065 23.282c-1.455 5.428-3.914 10.336-6.852 13.708m-13.585 0c-2.18-4.58-2.305-11.903-.331-19.272C13.997 14.351 18.926 7.26 23.891 5.5");
}

.lvo_2zbtq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.389 42.49c-3.55-2.526-7.008-6.465-9.693-11.115c-5.938-10.284-6.583-21.027-1.44-23.995c5.141-2.969 14.122 2.961 20.06 13.245c4.829 8.365 6.276 17.3 3.539 21.865");
}

.nl8s30bhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.506 32.319c-2.259 5.205-12.41 6.978-23.283 4.065c-5.428-1.455-10.357-3.914-13.729-6.852m.011-13.585c4.58-2.18 11.913-2.305 19.282-.331c8.793 2.356 15.889 7.226 17.719 12.157");
}

.pitsp82dj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.494 26.384c2.526-3.55 6.485-7.008 11.135-9.693c10.284-5.938 21.027-6.583 23.995-1.44c2.969 5.141-2.961 14.122-13.245 20.06c-8.357 4.824-17.29 6.274-21.859 3.545");
}

.thbvurb3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.23 23.9c0-2.287-1.891-4.14-4.225-4.14s-4.225 1.853-4.225 4.14v4.219c0 2.287 1.892 4.14 4.225 4.14c2.334 0 4.225-1.853 4.225-4.14h-4.225");
}

.xp5fiybkn {
  width: 37px;
  height: 37px;
  x: 5.505px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
