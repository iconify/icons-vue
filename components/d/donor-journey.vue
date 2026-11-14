<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2u42j8px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:donor-journey" /></template>
<style>
.o2u42j8px {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.334 11.624Q13.25 8.901 13.25 5.75q0-3.25 3-3.25q.918 0 1.5.47q.582-.47 1.5-.47q3 0 3 3.25q0 3.151-4.084 5.874q-.092.062-.199.094q-.106.032-.217.032t-.217-.032t-.199-.094M6.9 19.724q-.171.582-.632 1.044q-.732.732-1.768.732Q2 21.5 2 19t2.5-2.5q1.036 0 1.768.732q.438.438.614.985q2.411-.258 3.418-2.56q1.49-3.407 5.2-3.407q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-2.729 0-3.826 2.508q-1.396 3.193-4.774 3.466");
}

</style>
