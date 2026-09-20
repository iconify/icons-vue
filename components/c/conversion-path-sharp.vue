<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3fb_88gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:conversion-path-sharp" /></template>
<style>
.b3fb_88gb {
  fill: currentColor;
  d: path("M19 20.5q-.898 0-1.586-.562t-.855-1.438H11q-1.458 0-2.479-1.021T7.5 15t1.021-2.479T11 11.5h2q1.037 0 1.768-.732T15.5 9t-.732-1.768T13 6.5H7.44q-.17.875-.856 1.438T5 8.5q-1.038 0-1.77-.73T2.5 6t.73-1.77T5 3.5q.898 0 1.584.563q.685.562.857 1.437H13q1.458 0 2.479 1.021T16.5 9t-1.021 2.479T13 12.5h-2q-1.036 0-1.768.732T8.5 15t.732 1.768T11 17.5h5.56q.17-.875.856-1.437T19 15.5q1.039 0 1.77.73T21.5 18t-.73 1.77t-1.77.73M6.059 7.059Q6.5 6.617 6.5 6t-.441-1.059Q5.617 4.5 5 4.5t-1.059.441Q3.5 5.383 3.5 6t.441 1.059Q4.383 7.5 5 7.5t1.059-.441");
}

</style>
