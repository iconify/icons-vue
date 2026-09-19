<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r-xt7ywlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-tooth" /></template>
<style>
.r-xt7ywlt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.944 9.351A8.88 8.88 0 0 0 31.9 5.53c-3.667.416-4.623 2.108-7.899 2.43c-3.276-.322-4.232-2.014-7.899-2.43a8.88 8.88 0 0 0-8.047 3.82c-2.103 3.213-1.641 8.01 1.383 11.68a4.64 4.64 0 0 1 1.1 2.764c.182 4.667 1.07 17.795 5.33 18.684c3.286.686 1.549-15.016 8.132-14.813c6.583-.203 4.845 15.499 8.132 14.813c4.26-.889 5.148-14.017 5.33-18.684a4.64 4.64 0 0 1 1.1-2.764c3.024-3.67 3.486-8.467 1.382-11.679");
}

</style>
