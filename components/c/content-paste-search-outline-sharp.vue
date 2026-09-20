<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek8xzekyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:content-paste-search-outline-sharp" /></template>
<style>
.ek8xzekyv {
  fill: currentColor;
  d: path("M4 20V4h6.252q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985H20v6.692h-1V5h-3v2.23H8V5H5v14h5.5v1zm8.578-14.999q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23M20.292 21l-2.661-2.642q-.454.286-.977.464T15.577 19q-1.413 0-2.418-1.005t-1.005-2.418t1.005-2.418t2.418-1.005t2.418 1.005T19 15.577q0 .554-.159 1.087q-.158.532-.503.967L21 20.292zm-2.998-3.706q.706-.706.706-1.717t-.706-1.717t-1.717-.706t-1.718.706t-.705 1.717t.705 1.717q.707.706 1.718.706t1.717-.706");
}

</style>
