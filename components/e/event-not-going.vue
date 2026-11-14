<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnicgmbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:event-not-going" /></template>
<style>
.vnicgmbwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.475 4.5h8.15q.107 0 .215.005q.107.006.214.016t.213.026t.212.037t.209.047t.207.057t.204.068t.2.077t.197.087t.191.097q.095.05.187.105q.092.056.182.115q.089.06.175.124t.169.132t.163.14t.156.148t.148.156t.14.163t.132.169t.124.175t.115.182q.055.092.105.187q.051.094.097.191q.046.098.087.197t.077.2t.068.204q.031.103.057.207t.047.209t.037.212t.026.213t.016.214t.005.215v8.153m-3.524 4.388q-.421.084-.851.084h-9.25q-.107 0-.215-.005q-.107-.006-.214-.016t-.213-.026t-.212-.037t-.209-.047q-.104-.026-.207-.057t-.204-.068q-.101-.036-.2-.077t-.197-.087t-.191-.097q-.095-.05-.187-.105q-.092-.056-.182-.115q-.089-.06-.175-.124t-.169-.132t-.163-.14t-.156-.148t-.148-.156t-.14-.163t-.132-.169t-.124-.175t-.115-.182t-.105-.187q-.051-.094-.097-.191q-.046-.098-.087-.197t-.077-.2t-.068-.204t-.057-.207t-.047-.209q-.021-.106-.037-.212t-.026-.213t-.016-.214Q3 17.232 3 17.125v-8.25q0-.853.321-1.644M3 10h3.1m7.8 0H21M9 2.5v2.6m6-2.6V6M3.5 3.5l17 17");
}

</style>
