<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-s2b6bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-laundry-service-outline-sharp" /></template>
<style>
.k-s2b6bpg {
  fill: currentColor;
  d: path("M4 22V2h16v20zm2-2h12V4H6zm9.538-2.463Q17 16.076 17 14t-1.463-3.537T12 9t-3.537 1.463T7 14t1.463 3.538T12 19t3.538-1.463M12 17.3q-.65 0-1.263-.238T9.65 16.35l4.7-4.7q.475.475.713 1.088T15.3 14q0 1.375-.962 2.338T12 17.3M8 7q.425 0 .713-.288T9 6t-.288-.712T8 5t-.712.288T7 6t.288.713T8 7m3.713-.288Q12 6.426 12 6t-.288-.712T11 5t-.712.288T10 6t.288.713T11 7t.713-.288M6 20V4z");
}

</style>
