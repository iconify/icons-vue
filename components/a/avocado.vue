<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lzh2ksbeb"/><path class="d_-g9zu8u"/><path class="z5cv5mwbb"/><path class="l0u7bobli"/><path class="zljt0xout"/><path class="o-94yjbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:avocado" /></template>
<style>
.d_-g9zu8u {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M20.605 26.03c-6.523 4.546-15.287 5.15-18.469.582c-3.183-4.566.418-12.578 6.943-17.124c6.522-4.545 21.951-9.796 25.134-5.23c3.183 4.57-7.085 17.226-13.608 21.772");
}

.l0u7bobli {
  fill: var(--svg-color--c6e5b3, #c6e5b3);
  d: path("M18.169 23.926c-4.506 3.14-9.939 3.127-12.136-.027c-2.2-3.154-.33-8.255 4.176-11.395c4.507-3.141 15.835-7.238 18.035-4.084s-5.567 12.366-10.075 15.506");
}

.lzh2ksbeb {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M35 5.904c2.394 6.042-1.438 20.543-10.5 26.5c-9.06 5.957-20.395 3.573-23.097-6.443c-1.669-6.186 2.79-10.721 11.851-16.677C22.315 3.327 32.64-.053 35 5.904");
}

.o-94yjbkd {
  fill: var(--svg-color--7c3225, #7c3225);
  d: path("M13.071 13.106c1.51-1.013 3.414-.819 4.254.431c.837 1.251.294 3.087-1.217 4.1c-1.51 1.01-3.414.817-4.253-.433c-.839-1.252-.294-3.086 1.216-4.098");
}

.z5cv5mwbb {
  fill: var(--svg-color--a6d388, #a6d388);
  d: path("M19.815 26.578c-5.757 4.013-13.482 3.097-16.29-.934S4 14.474 9.757 10.463c5.755-4.011 20.258-9.264 23.068-5.234c2.807 4.03-4.825 16.175-13.01 21.349");
}

.zljt0xout {
  fill: var(--svg-color--662113, #662113);
  d: path("M11.162 12.488c3.48-2.332 7.382-1.495 9.798.995c1.433 1.477-.88 5.382-4.359 7.714c-3.478 2.33-7.769 1.763-8.239.731c-1.44-3.157-.677-7.109 2.8-9.44");
}

</style>
