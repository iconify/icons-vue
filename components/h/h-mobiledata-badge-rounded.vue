<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm3xhq8jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:h-mobiledata-badge-rounded" /></template>
<style>
.fm3xhq8jv {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm4.076-7.5h4.616V16q0 .214.143.357t.357.143t.357-.143t.143-.357V8q0-.213-.144-.357t-.356-.143t-.357.143t-.143.357v3.5H9.692V8q0-.213-.143-.357T9.192 7.5t-.357.143T8.692 8v8q0 .214.143.357t.357.143t.357-.143t.143-.357z");
}

</style>
