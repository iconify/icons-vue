<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr97o7bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lips" /></template>
<style>
.wr97o7bdg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.876 12.416Q6.099 18.75 12 18.75t10.124-6.334q-.059.088-.14.157q-.081.068-.178.112q-.097.043-.202.058q-.105.014-.21-.001q-1.572-.224-4.532.192q-3.166.445-4.862.086q-1.696.359-4.862-.086q-2.96-.416-4.532-.192q-.105.015-.21.001q-.105-.015-.202-.058t-.178-.112t-.14-.157M22.1 11.55q-4.725-6.3-8.1-6.3q-.8 0-1.739.584q-.19.118-.261.152q-.071-.034-.261-.152Q10.8 5.25 10 5.25q-3.375 0-8.099 6.299q.089-.119.217-.195q.128-.075.276-.096q1.782-.255 4.953.191q3.05.429 4.471.073q.182-.045.364 0q1.421.356 4.471-.073q3.171-.446 4.953-.191q.148.021.276.097t.218.195");
}

</style>
