<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqgahrb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:google-guarantee" /></template>
<style>
.hqgahrb1u {
  fill: currentColor;
  d: path("M12.025 21.025q-3.425 0-5.725-2.475T4 12.725V5.5q0-.825.588-1.413Q5.175 3.5 6 3.5h12q.825 0 1.413.587Q20 4.675 20 5.5v1.75q0 .4-.15.762q-.15.363-.425.638l-5.775 5.775q-.575.575-1.412.575q-.838 0-1.413-.575L8 11.6l1.4-1.425L12.25 13L18 7.25V5.5H6v7.3q0 2.55 1.725 4.375Q9.45 19 12.025 19q2.5 0 4.237-1.75Q18 15.5 18 13h2q0 3.35-2.312 5.688q-2.313 2.337-5.663 2.337Z");
}

</style>
