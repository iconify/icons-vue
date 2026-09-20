<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb5ffvb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:child-care-outline-rounded" /></template>
<style>
.zb5ffvb4t {
  fill: currentColor;
  d: path("M13.718 11.166q-.276-.276-.276-.666t.276-.666t.667-.276t.666.276t.276.666t-.276.666t-.666.276t-.667-.276m-4.769 0q-.276-.276-.276-.666t.276-.666t.667-.276t.666.276t.276.666t-.276.666t-.666.276t-.667-.276m.829 4.461Q8.768 15.023 8.154 14h7.692q-.613 1.023-1.624 1.627q-1.01.604-2.222.604t-2.222-.604m-.896 3.747q-1.455-.626-2.542-1.713t-1.714-2.543T4 12t.626-3.118T6.34 6.34t2.542-1.714T12 4t3.118.626T17.66 6.34t1.714 2.542T20 12t-.626 3.118t-1.714 2.542t-2.542 1.714T12 20t-3.118-.626m8.068-2.424Q19 14.9 19 12t-2.05-4.95T12 5q-.265 0-.54.02t-.522.069q-.073.188-.084.325q-.012.136-.012.336q0 .64.459 1.099t1.099.459q.283 0 .441-.075t.359-.075q.166 0 .279.129t.113.313q0 .344-.383.468q-.384.124-.809.124q-1.01 0-1.726-.716T9.958 5.75v-.208q0-.094.044-.238q-2.171.635-3.587 2.458Q5 9.585 5 12q0 2.9 2.05 4.95T12 19t4.95-2.05M12 12");
}

</style>
