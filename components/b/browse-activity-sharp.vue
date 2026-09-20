<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atmuzqb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:browse-activity-sharp" /></template>
<style>
.atmuzqb6c {
  fill: currentColor;
  d: path("M1 21v-2h22v2zm1-3v-7h5.375l2 4h1.2l3.375-5.875l.925 1.875H22v7zm8.075-6.125L8.6 9H2V3h20v6h-5.875l-1.5-3h-1.2z");
}

</style>
