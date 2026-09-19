<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vprym5x7f"/><path class="y7ce7obxq"/><path class="u7s-jmbfl"/><path class="thgikbjos"/><path class="xykzd-b0e"/><path class="qitg2mb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-womans-hat" /></template>
<style>
.qitg2mb3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.876 25.692s3.857.443 9.124.443q.74 0 1.44-.01");
}

.thgikbjos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.765 25.964a88 88 0 0 0 1.755-.122");
}

.u7s-jmbfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.782 24.814c-5.547.76-9.282 2.184-9.282 3.815c0 2.43 8.283 4.4 18.5 4.4s18.523-1.97 18.5-4.4c-.022-2.335-3.483-3.462-7.264-3.815");
}

.vprym5x7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.313 28.733a1.946 1.946 0 0 1-1.985-1.905a1.946 1.946 0 0 1 1.903-1.988c2.636-.056 3.586 2.658 3.609 3.733z");
}

.xykzd-b0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.162 24.427c-.39-3.952-2.193-9.494-9.256-9.455c-10.971.059-9.03 13.343-9.03 13.343s3.857.536 9.124.536c2.843 0 5.39-.144 6.765-.245");
}

.y7ce7obxq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.283 28.31a1.946 1.946 0 0 0-.42-3.871c-2.621.285-3.214 3.098-3.098 4.167z");
}

</style>
