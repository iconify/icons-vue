<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8rk-ybtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:avg-time-outline-sharp" /></template>
<style>
.g8rk-ybtu {
  fill: currentColor;
  d: path("M8.888 20.374q-1.455-.626-2.546-1.716t-1.716-2.545T4 13h1q0 2.9 2.05 4.95T12 20t4.95-2.05T19 13h1q0 1.658-.626 3.113t-1.716 2.545t-2.546 1.716T12 21t-3.113-.626M4 13q0-1.658.626-3.113t1.716-2.545t2.546-1.716T12 5q1.454 0 2.812.52t2.492 1.469l1.092-1.093l.708.708l-1.092 1.092q.95 1.135 1.469 2.493T20 13h-1q0-2.9-2.05-4.95T12 6T7.05 8.05T5 13zM9.385 2.5v-1h5.23v1zM7.216 7.879Q5.2 9.758 5.017 12.5h3.3l1.666 3.304L14 8l2.312 4.5h2.67q-.182-2.742-2.2-4.621Q14.767 6 12 6T7.217 7.879m9.566 10.242q2.017-1.879 2.2-4.621h-3.3l-1.666-3.304L10 18l-2.311-4.5H5.016q.183 2.742 2.2 4.621T12 20t4.783-1.879M7.05 17.95Q5 15.9 5 13t2.05-4.95T12 6t4.95 2.05T19 13t-2.05 4.95T12 20t-4.95-2.05M12 13");
}

</style>
