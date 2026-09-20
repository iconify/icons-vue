<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s56m-kb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:find-in-page-outline-sharp" /></template>
<style>
.s56m-kb8b {
  fill: currentColor;
  d: path("m15.442 20l1 1H5V3h9.539L19 8.346v12.27h-.092L13.73 15.45q-.425.294-.839.422Q12.48 16 12 16q-1.246 0-2.123-.877T9 13t.877-2.123T12 10t2.123.877T15 13q0 .517-.137.93t-.413.8l3.55 3.6V8.7L14.05 4H6v16zm-2.03-5.587Q14 13.825 14 13t-.587-1.412T12 11t-1.412.588T10 13t.588 1.413T12 15t1.413-.587M12 12");
}

</style>
