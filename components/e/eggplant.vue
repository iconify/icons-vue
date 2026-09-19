<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kskeq2lng"/><path class="ddi62zb4s"/><g class="s_7-d6zqd"><path class="osaqrsbtv"/><path class="fx48bebsl"/></g><path class="o-zerkbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:eggplant" /></template>
<style>
.ddi62zb4s {
  d: path("M10 27.9c2.2-2.6 1.6-6.9 1.6-6.9s1.7 2 4.2 2l.2-4.4s3.8-.1 7.1-3.8l-11.2-.4L8 20.8z");
  opacity: var(--svg-opacity--0-15, 0.15);
}

.fx48bebsl {
  d: path("M17.2 16.2c3.8.4 7.3-2.6 7.3-2.6s-2.6-3.6-6.5-4c-3.8-.4-7.1.7-7.3 2.5c-.2 1.9 2.7 3.7 6.5 4.1m-12.1 4c-.5 4 2 7.5 2 7.5s3.2-2.9 3.7-6.9s-.4-7.3-2-7.5c-1.6-.1-3.2 3-3.7 6.9");
}

.kskeq2lng {
  fill: var(--svg-color--7a2d77, #7a2d77);
  d: path("M53.4 34.4c-7.6-9.1-19.5-10.3-30.6-21.1c-6.7-6.5-18.5 6.4-15.3 12.6c4.3 8.2 14.2 23.9 23.1 30.8c19.1 14.7 38.2-3.9 22.8-22.3");
}

.o-zerkbej {
  fill: var(--svg-color--8cc63e, #8cc63e);
  d: path("M8.7 18c2.5 3.5 7.9 3.5 7.9 3.5s1.2-5.7-1.3-9.3c-2.5-3.5-6.1-5.1-7.9-3.5c-1.9 1.6-1.3 5.7 1.3 9.3");
}

.osaqrsbtv {
  d: path("m10.9 12.5l-.9 1.6C7.6 12.5 4.2 8.1 7.6 2l1.5 1c-3.1 5.5 1.3 9.1 1.8 9.5");
}

.s_7-d6zqd {
  fill: var(--svg-color--83b730, #83b730);
}

</style>
