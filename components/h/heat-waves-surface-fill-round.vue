<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eorg1bkfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heat-waves-surface-fill-round" /></template>
<style>
.eorg1bkfp {
  fill: currentColor;
  d: path("M6.253 12.336c1.14-1.284 1.14-2.388 0-3.672C5.467 7.78 4.889 6.708 4.889 5.5s.578-2.28 1.364-3.164a.999.999 0 1 1 1.494 1.328C7.298 4.17 6.889 4.8 6.889 5.5s.409 1.33.858 1.836c1.819 2.047 1.819 4.281 0 6.328a.999.999 0 1 1-1.494-1.328m5 0c1.14-1.284 1.14-2.388 0-3.672c-.786-.884-1.364-1.956-1.364-3.164s.578-2.28 1.364-3.164a.999.999 0 1 1 1.494 1.328c-.449.506-.858 1.136-.858 1.836s.409 1.33.858 1.836c1.819 2.047 1.819 4.281 0 6.328a.999.999 0 1 1-1.494-1.328m5 0c1.14-1.284 1.14-2.388 0-3.672c-1.819-2.047-1.819-4.281 0-6.328a1 1 0 0 1 1.494 1.328c-.449.506-.858 1.136-.858 1.836s.409 1.33.858 1.836c.786.884 1.364 1.956 1.364 3.164s-.578 2.28-1.364 3.164a.999.999 0 1 1-1.494-1.328M5 16h14a3 3 0 1 1 0 6H5a3 3 0 1 1 0-6");
}

</style>
