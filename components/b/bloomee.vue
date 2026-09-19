<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f13zqd4_l"/><path class="r6noffb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bloomee" /></template>
<style>
.f13zqd4_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.047 26.39l-7.122 3.818a1.21 1.21 0 0 1-1.785-1.068v-7.635a1.21 1.21 0 0 1 1.785-1.068l7.122 3.818a1.21 1.21 0 0 1 0 2.136");
}

.r6noffb_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.565 20.225l1.49-2.343c-2.278-3.397-9.565-4.168-12.802-1.16c.726-1.69.985-3.59.339-5.867c-1.118-3.932-4.43-5.632-4.972-5.898l-1.6 2.074l-1.841-2.074c-3.807 1.228-6.519 7.757-4.759 11.728c-3.4-2.704-10.4-1.73-12.552 1.646l1.544 2.306L4 21.662c.121.591.928 4.225 4.454 6.297c1.596.938 3.109 1.282 4.562 1.255c-1.144.908-2.096 2.142-2.729 3.89c-1.394 3.845.305 7.16.589 7.692l2.51-.751l.283 2.76c3.51 1.131 8.893-1.936 10.413-5.751c1.56 3.8 6.972 6.813 10.47 5.647l.256-2.764l2.518.73c.278-.536 1.942-3.866.51-7.697c-.688-1.843-1.73-3.107-2.97-4.016c1.547.045 3.149-.318 4.829-1.359c3.476-2.155 4.198-5.807 4.305-6.401z");
}

</style>
