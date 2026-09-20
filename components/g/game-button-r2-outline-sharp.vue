<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn3nis1iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-r2-outline-sharp" /></template>
<style>
.xn3nis1iu {
  fill: currentColor;
  d: path("M3 19V8.27q0-1.362.973-2.326q.973-.963 2.354-.963h11.346q1.38 0 2.354.963Q21 6.908 21 8.27V19zm1-1h16V8.27q0-.96-.684-1.625q-.683-.664-1.643-.664H6.327q-.96 0-1.643.664Q4 7.31 4 8.27zm0 0h16zm3.135-2.829h.856v-2.467h1.175l1.555 2.467h.99l-1.723-2.686q.623-.218.938-.644q.314-.425.314-1.06q0-.933-.56-1.377T8.96 8.96H7.134zm.856-3.229l-.02-2.161h.938q.708 0 1.07.275t.362.78q0 .531-.354.819t-1.006.287zm4.898 3.235h4.169v-.84h-3.064v-.056l1.34-1.202q.807-.742 1.146-1.31q.34-.569.34-1.219q0-.802-.526-1.264t-1.402-.463q-.578 0-1.063.251t-.892.745l.54.508q.371-.388.682-.537q.31-.148.722-.148q.483 0 .777.266q.294.265.294.704q0 .501-.279.938t-1.038 1.19l-1.747 1.664z");
}

</style>
