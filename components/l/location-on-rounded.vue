<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igdsy3b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:location-on-rounded" /></template>
<style>
.igdsy3b3z {
  fill: currentColor;
  d: path("M11.53 20.479q-.234-.077-.432-.25q-1.067-.981-2.164-2.185q-1.095-1.203-1.99-2.493t-1.468-2.633t-.572-2.622q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 1.279-.572 2.613q-.572 1.333-1.458 2.632q-.885 1.3-1.981 2.494T12.92 20.21q-.198.173-.442.26t-.479.086t-.47-.077m1.613-9.22q.472-.472.472-1.143q0-.672-.472-1.144T12 8.5t-1.143.472t-.472 1.144t.472 1.143T12 11.73t1.143-.472");
}

</style>
