<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpdzhb2fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arepa" /></template>
<style>
.cpdzhb2fc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.6 12.673q-.963.321-1.865-.144q-.903-.464-1.202-1.434Q1.817 8.77 4.126 8L17.4 3.577q.963-.322 1.865.143q.903.464 1.202 1.434q.716 2.326-1.593 3.096zm2.001 2.577h10.946q-.164-.243-.463-.385q-.765-.364-1.789.074q-.152.066-.317.061t-.313-.079q-2.665-1.332-5.33 0q-.125.063-.266.076q-.14.013-.275-.026q-1.067-.305-1.878.081q-.183.087-.315.198m12.589.088q2.06.426 2.06 2.912q0 1.243-.879 2.121q-.878.879-2.121.879H4.75q-1.243 0-2.121-.879q-.879-.878-.879-2.121q0-3 3-3h1.099q.289-1.013 1.422-1.552q1.205-.574 2.651-.242q3.054-1.41 6.108-.023q1.459-.513 2.699.077q1.218.58 1.461 1.828");
}

</style>
