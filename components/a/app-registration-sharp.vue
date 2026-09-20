<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo384jb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:app-registration-sharp" /></template>
<style>
.eo384jb2y {
  fill: currentColor;
  d: path("M5.126 18.874q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m0-6q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m0-6Q4.769 6.517 4.769 6t.357-.874T6 4.769t.874.357t.357.874t-.357.874T6 7.231t-.874-.357m6 0q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m6 0q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m-6 6q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m2.105 6.357v-2.21l5.96-5.934l2.19 2.204l-5.94 5.94zm5.96-4.985l.925-.956l-.925-.944l-.95.95z");
}

</style>
