<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ijmj0gblp"/><path class="w18c2nb2x"/><path class="kecllx9gi"/><path class="tppzg8bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:canoe" /></template>
<style>
.ijmj0gblp {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M33.793 17S32.476 20 18 20C3.523 20 1.973 17 1.973 17S-1 22.117 4.802 25c4.238 2.105 10.916-.131 12.723-.814c1.991.683 9.274 2.824 13.557.814c5.862-2.751 2.711-8 2.711-8");
}

.kecllx9gi {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M27.005 25.389a.805.805 0 0 0 .569-1.375l-8.861-8.86a.805.805 0 1 0-1.139 1.139l8.861 8.86a.8.8 0 0 0 .57.236");
}

.tppzg8bme {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M29.316 28.505a1.61 1.61 0 0 0 1.139-2.75l-2.416-2.416a1.61 1.61 0 0 0-2.278 2.278l2.416 2.416c.314.315.727.472 1.139.472");
}

.w18c2nb2x {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M0 24h36v12H0z");
}

</style>
