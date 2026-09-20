<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps7g08b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keep-public-sharp" /></template>
<style>
.ps7g08b2x {
  fill: currentColor;
  d: path("m9 20.5l-.5-.5v-5H4.423v-1L6 12.423V5H5V4h6.048q-.698.846-1.065 1.874Q9.615 6.902 9.615 8q0 1.952 1.088 3.54t2.874 2.289V15H9.5v5zm4.165-9.664Q12 9.67 12 8t1.165-2.835T16 4t2.836 1.165T20 8t-1.164 2.836T16 12t-2.835-1.164m3.898-3.274q.437-.437.437-1.062t-.437-1.062T16 5t-1.062.438T14.5 6.5t.438 1.063T16 8t1.063-.437m.34 3.084q.647-.353 1.072-.972q-.57-.344-1.194-.51Q16.656 9 16 9t-1.28.166q-.626.165-1.195.509q.425.62 1.072.972Q15.244 11 16 11t1.403-.353");
}

</style>
