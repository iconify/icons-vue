<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks7hmpppn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:familiar-face-and-zone-sharp" /></template>
<style>
.ks7hmpppn {
  fill: currentColor;
  d: path("M12.003 19q-2.93 0-4.966-2.033T5 12.003t2.034-4.966T11.997 5t4.967 2.034T19 11.997t-2.033 4.967T12.003 19M12 18q2.5 0 4.25-1.75T18 12q0-.435-.062-.857q-.063-.422-.188-.831q-.394.094-.793.141q-.4.047-.798.047q-1.676 0-3.169-.706q-1.492-.705-2.579-1.971q-.623 1.444-1.761 2.523Q7.511 11.425 6 11.94q.017 2.488 1.764 4.275Q9.511 18 12 18m-2.978-4.522q-.272-.272-.272-.674t.272-.69t.674-.287t.69.288t.287.689t-.288.674t-.689.272t-.674-.272m4.615 0q-.271-.272-.271-.674t.271-.69t.675-.287t.689.288t.288.689t-.288.674t-.69.272t-.674-.272M2 6V2h4v1H3v3zm0 16v-4h1v3h3v1zm16 0v-1h3v-3h1v4zm3-16V3h-3V2h4v4z");
}

</style>
