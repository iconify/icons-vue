<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dgxk2fbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-triangular-flag" /></template>
<style>
.dgxk2fbvs {
  fill: currentColor;
  d: path("M54.896 18.592L19.103 2h-3.752v55.405C11.155 57.624 8 58.558 8 59.679C8 60.961 12.132 62 17.229 62c5.091 0 9.223-1.039 9.223-2.321c0-1.121-3.155-2.055-7.349-2.273V39.018c4.322-2.002 33.981-15.751 35.794-16.593c1.471-.682 1.471-3.15-.001-3.833");
}

</style>
