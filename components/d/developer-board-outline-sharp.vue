<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwtu1jp0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:developer-board-outline-sharp" /></template>
<style>
.bwtu1jp0e {
  fill: currentColor;
  d: path("M3.23 20V4h16v3.77h1.54v1h-1.54v2.73h1.54v1h-1.54v2.73h1.54v1h-1.54V20zm1-1h14V5h-14zM7 16.23h4.039v-3.038H7zm5.423-6.422h3.039V7.769h-3.039zm-5.423 2h4.039V7.769H7zm5.423 4.423h3.039v-5.039h-3.039zM4.231 19V5z");
}

</style>
