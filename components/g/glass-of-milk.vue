<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="n5g78u8tb"/><path class="smyrar2uu"/><path class="ro7uadbex"/><path class="q-1q51boq"/><path class="ypy309lhz"/><path class="nfe4b2bgp"/><path class="nwbez7byj"/><ellipse class="yk8d6trbe"/><path class="dpmjrvnja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:glass-of-milk" /></template>
<style>
.dpmjrvnja {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M11.042 31.542h14.167v1.833H11.042z");
}

.n5g78u8tb {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M8.777 4.458L10.792 32h14.333l2.189-27.562z");
}

.nfe4b2bgp {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M29 4.083c0 1.703-2.73 3.083-11 3.083S7 5.786 7 4.083S9.73 1 18 1s11 1.38 11 3.083");
}

.nwbez7byj {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.532 4.128a1 1 0 0 0-1.387-.276c-2.086 1.393-7.274 1.571-9.097 1.523c-.01-.001-.019.005-.029.004c-.009 0-.016-.004-.025-.004c-1.819.049-7.008-.127-9.097-1.523a1 1 0 0 0-1.111 1.663c2.57 1.717 7.917 1.866 9.688 1.866c.289 0 .477-.004.547-.006c.071.002.258.006.547.006c1.771 0 7.118-.148 9.688-1.866a1 1 0 0 0 .276-1.387");
}

.q-1q51boq {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M18 33h-2.627c-5.532 0-6.167-2.684-6.46-6.474C8.585 22.295 7.16 4.432 7.16 4.432l1.993-.159s1.427 17.868 1.754 22.099c.265 3.439.556 4.628 4.466 4.628H18a1 1 0 1 1 0 2");
}

.ro7uadbex {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M23.906 35.175H12.094c-1.712 0-2.914-1.153-3.135-3.011L6.984 4.448a1.175 1.175 0 0 1 1.089-1.255a1.17 1.17 0 0 1 1.255 1.088l1.969 27.66c.107.884.573.884.797.884h11.812c.516 0 .708 0 .8-.917l1.966-27.627a1.175 1.175 0 0 1 2.344.167l-1.969 27.659c-.252 2.541-1.847 3.068-3.141 3.068");
}

.smyrar2uu {
  fill: var(--svg-color--fff, #fff);
  d: path("m25 31.281l-14.094.157l-1.018-15.312h16.246z");
}

.yk8d6trbe {
  cx: 17.991px;
  cy: 16.06px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  rx: 7.827px;
  ry: 1.464px;
}

.ypy309lhz {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M20.627 33H18a1 1 0 1 1 0-2h2.627c3.91 0 4.2-1.189 4.466-4.628c.328-4.232 1.754-22.099 1.754-22.099l1.994.159s-1.426 17.864-1.754 22.094c-.293 3.79-.927 6.474-6.46 6.474");
}

</style>
