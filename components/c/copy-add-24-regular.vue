<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6pyogtei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-add-24-regular" /></template>
<style>
.k6pyogtei {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-9-3.5H5.25a1.75 1.75 0 0 0-1.75 1.75v8.5c0 .966.784 1.75 1.75 1.75h6c.157 0 .308-.023.452-.061c.235.462.524.893.858 1.284a3.2 3.2 0 0 1-1.31.277h-6A3.25 3.25 0 0 1 2 18.75v-8.5A3.25 3.25 0 0 1 5.25 7H8.5zm9 5.499a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5M18.75 2A3.25 3.25 0 0 1 22 5.25v7.562a6.5 6.5 0 0 0-1.5-1.079V5.25a1.75 1.75 0 0 0-1.75-1.75h-6A1.75 1.75 0 0 0 11 5.25v8.5c0 .48.193.914.506 1.23a6.5 6.5 0 0 0-.435 1.553A3.25 3.25 0 0 1 9.5 13.75v-8.5A3.25 3.25 0 0 1 12.75 2z");
}

</style>
