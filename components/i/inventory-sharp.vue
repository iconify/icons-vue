<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t763xpbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:inventory-sharp" /></template>
<style>
.t763xpbdt {
  fill: currentColor;
  d: path("m15.5 19.214l-3.558-3.558l.708-.708l2.85 2.85l5.689-5.688l.707.707zM20 10h-1V5h-3v2.23H8V5H5v14h6v1H4V4h6.252q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985H20zm-7.422-4.999q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23");
}

</style>
