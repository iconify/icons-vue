<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgpnlib1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-laundry-service-sharp" /></template>
<style>
.hgpnlib1n {
  fill: currentColor;
  d: path("M5 21V3h14v18zm9.99-4.01q1.24-1.242 1.24-2.99t-1.24-2.99Q13.747 9.77 12 9.77t-2.99 1.24Q7.77 12.253 7.77 14t1.24 2.99q1.242 1.24 2.99 1.24t2.99-1.24M12 17.3q-.65 0-1.253-.247t-1.059-.703l4.662-4.661q.456.455.703 1.058T15.3 14q0 1.375-.962 2.338T12 17.3M8 7q.425 0 .713-.288T9 6t-.288-.712T8 5t-.712.288T7 6t.288.713T8 7m3.713-.288Q12 6.426 12 6t-.288-.712T11 5t-.712.288T10 6t.288.713T11 7t.713-.288");
}

</style>
