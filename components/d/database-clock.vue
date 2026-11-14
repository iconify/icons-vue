<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwxredced"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-clock" /></template>
<style>
.rwxredced {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2Q3.25 2 3.25 5.5v13Q3.25 22 12 22t8.75-3.5v-13Q20.75 2 12 2m8.75 3.5Q20.75 9 12 9T3.25 5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 4.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .592 1.844 1.228Q8.832 7.5 12 7.5t5.406-.772Q19.25 6.092 19.25 5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T20 4.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M8.995 11.745Q10.24 10.5 12 10.5t3.005 1.245t1.245 3.005t-1.245 3.005T12 19t-3.005-1.245T7.75 14.75t1.245-3.005");
}

</style>
