<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qqnm6bcko"/><path class="ulbschf4v"/><path class="duporv-yi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-on-delivery" /></template>
<style>
.duporv-yi {
  d: path("M18.75 17c-.25-.5-.5-.5-.75-.5q-.75 0-.75.75c0 .5 1.5.5 1.5 1.5q0 .75-.75.75c-.5 0-.75-.25-.75-.5m.75-3.25v.75m0 3v.75");
}

.qqnm6bcko {
  d: path("M2.5 2.5h11v9h-11Zm11 2.5H17l3.5 3.5v3h-.55m-3.9 0H13.5");
}

.ulbschf4v {
  d: path("M2.5 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.5-.043q-.003-.097-.014-.193q-.011-.097-.032-.191q-.021-.095-.051-.187t-.068-.181t-.085-.174t-.102-.165t-.118-.154q-.062-.074-.131-.141q-.069-.068-.145-.129t-.156-.114t-.167-.098t-.176-.082q-.089-.036-.182-.064t-.188-.047t-.192-.028T11 11.5q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T9 13.5t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.361 0 .699-.126M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
