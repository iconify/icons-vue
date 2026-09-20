<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_i508bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:app-registration-outline-sharp" /></template>
<style>
.l_i508bec {
  fill: currentColor;
  d: path("M5.126 18.874q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m0-6q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m0-6Q4.769 6.517 4.769 6t.357-.874T6 4.769t.874.357t.357.874t-.357.874T6 7.231t-.874-.357m6 0q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m6 0q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m-6 6q-.357-.357-.357-.874t.357-.874t.874-.357t.874.357t.357.874t-.357.874t-.874.357t-.874-.357m2.105 6.357v-2.21l5.96-5.934l2.19 2.204l-5.94 5.94zm6.885-5.94l-.925-.945zm-6 5.055h.95l3.467-3.473l-.47-.475l-.455-.489l-3.492 3.487zm3.948-3.948l-.456-.489l.925.964z");
}

</style>
