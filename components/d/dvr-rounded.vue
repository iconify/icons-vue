<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ite1aibrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dvr-rounded" /></template>
<style>
.ite1aibrf {
  fill: currentColor;
  d: path("M7.434 13.434q.182-.182.182-.434t-.182-.434T7 12.385t-.434.181t-.181.434t.181.434t.434.182t.434-.182m0-4q.182-.182.182-.434t-.182-.434T7 8.385t-.434.181T6.385 9t.181.434t.434.182t.434-.182M9.616 13.5H17q.214 0 .357-.143T17.5 13t-.143-.357T17 12.5H9.616q-.214 0-.357.143T9.116 13t.143.357t.357.143m0-4H17q.214 0 .357-.143T17.5 9t-.143-.357T17 8.5H9.616q-.214 0-.357.143T9.116 9t.143.357t.357.143m-5 8.5q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v10.769q0 .69-.463 1.153T19.385 18H15v1.192q0 .349-.23.578t-.578.23H9.808q-.348 0-.578-.23T9 19.192V18z");
}

</style>
