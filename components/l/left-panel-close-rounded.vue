<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om8vjs87c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:left-panel-close-rounded" /></template>
<style>
.om8vjs87c {
  fill: currentColor;
  d: path("M15.596 14.204V9.799q0-.276-.252-.382t-.449.092l-1.931 1.932q-.237.236-.237.559t.242.566l1.927 1.926q.196.197.448.096t.252-.384M5.616 20q-.667 0-1.141-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h12.77q.666 0 1.14.475T20 5.615v12.77q0 .666-.475 1.14t-1.14.475zM9 19h9.385q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T18.384 5H9z");
}

</style>
