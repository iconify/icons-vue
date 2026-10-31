<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="vpuq-hbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-checkmark-28-regular" /></template>
<style>
.vpuq-hbyl {
  fill: currentColor;
  d: path("M12.592 3.496a2.25 2.25 0 0 1 2.816 0l7.75 6.218c.532.427.842 1.073.842 1.756v11.28A2.25 2.25 0 0 1 21.75 25H6.25A2.25 2.25 0 0 1 4 22.75V11.47c0-.683.31-1.33.842-1.756zm1.878 1.17a.75.75 0 0 0-.94 0l-7.75 6.219a.75.75 0 0 0-.28.585v11.28c0 .414.336.75.75.75h15.5a.75.75 0 0 0 .75-.75V11.47a.75.75 0 0 0-.28-.585zm2.75 7.804a.75.75 0 1 1 1.06 1.06l-5.25 5.25a.75.75 0 0 1-1.06 0l-2.25-2.25a.75.75 0 0 1 1.06-1.06l1.72 1.72z");
}

</style>
