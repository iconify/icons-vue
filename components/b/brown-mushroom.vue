<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lu2cfgrvd"/><path class="hvhtl0v6e"/><path class="x2xqpnbuy"/><path class="efzz4wbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:brown-mushroom" /></template>
<style>
.efzz4wbqq {
  fill: var(--svg-color--c87d5e, #c87d5e);
  d: path("M26.1 23.5c-4.5 4.4-6.9 12.7-3.4 16.6c3.3 3.6 9.3.8 13.4-3.4s8.1-9.7 5.8-14.5c-2.9-5.8-10.7-3.7-15.8 1.3");
}

.hvhtl0v6e {
  fill: var(--svg-color--e8d4af, #e8d4af);
  d: path("M35 113.2c1.2 5.5 8.7 7.6 8.7 7.6s10.8.6 17.7-.3c7-1 12.8-2.6 13.4-6.7s.4-6.9.2-11.2c-.1-1.9-.3-7.2-.3-7.2s-8 .4-18.7-.4c-10.5-.8-16.2-3.3-16.2-3.3s-1.5 6.9-2.6 9.7c-1.1 2.6-3.4 6.3-2.2 11.8");
}

.lu2cfgrvd {
  fill: var(--svg-color--c4a878, #c4a878);
  d: path("M40 75.5s.5 6.7.3 10.1s-.6 6.3-.6 6.3l3.2 25.8l.2 2.7s5.6 3.3 17.3 3.3c17.5 0 25.3-2.8 27.9-8.4c2.1-4.5-1.6-14.7-2.3-18.2c-2.5-11.6-1-20-1-20z");
}

.x2xqpnbuy {
  fill: var(--svg-color--a65f3e, #a65f3e);
  d: path("M62.7 4.3C23.6 4.2 6 30.7 6.6 57.1C7.3 80.8 43.5 83.7 61.5 84c27 .4 59.2-5.1 59.8-27.6c.8-26.2-18.3-52.1-58.6-52.1");
}

</style>
