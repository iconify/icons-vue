<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="semtvb44m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:familiar-face-and-zone" /></template>
<style>
.semtvb44m {
  fill: currentColor;
  d: path("M12.003 19q-2.93 0-4.966-2.033T5 12.003t2.034-4.966T11.997 5t4.967 2.034T19 11.997t-2.033 4.967T12.003 19M12 18q2.5 0 4.25-1.75T18 12q0-.435-.062-.857q-.063-.422-.188-.831q-.394.094-.793.141q-.4.047-.798.047q-1.676 0-3.169-.706q-1.492-.705-2.579-1.971q-.623 1.444-1.761 2.523Q7.511 11.425 6 11.94q.017 2.488 1.764 4.275Q9.511 18 12 18m-2.978-4.522q-.272-.272-.272-.674t.272-.69t.674-.287t.69.288t.287.689t-.288.674t-.689.272t-.674-.272m4.615 0q-.271-.272-.271-.674t.271-.69t.675-.287t.689.288t.288.689t-.288.674t-.69.272t-.674-.272M2 6V3.616q0-.691.463-1.153T3.616 2H6v1H3.616q-.232 0-.424.192T3 3.616V6zm4 16H3.616q-.691 0-1.153-.462T2 20.385V18h1v2.385q0 .23.192.423t.423.192H6zm12 0v-1h2.385q.23 0 .423-.192t.192-.424V18h1v2.385q0 .69-.462 1.152T20.385 22zm3-16V3.616q0-.232-.192-.424T20.385 3H18V2h2.385q.69 0 1.152.463T22 3.616V6z");
}

</style>
