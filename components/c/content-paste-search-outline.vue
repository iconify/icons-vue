<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jprjz8bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-paste-search-outline" /></template>
<style>
.jprjz8bjg {
  fill: currentColor;
  d: path("m20.292 21l-2.661-2.642q-.454.286-.977.464T15.577 19q-1.413 0-2.418-1.005t-1.005-2.418t1.005-2.418t2.418-1.005t2.418 1.005T19 15.577q0 .554-.159 1.087q-.158.532-.503.967L21 20.292zm-2.998-3.706q.706-.706.706-1.717t-.706-1.717t-1.717-.706t-1.718.706t-.705 1.717t.705 1.717q.707.706 1.718.706t1.717-.706M20 10.692h-1V5.616q0-.231-.192-.424T18.384 5H16v2.23H8V5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192H10.5v1H5.616q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.636q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985h4.63q.672 0 1.144.472T20 5.616zm-7.422-5.691q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23");
}

</style>
