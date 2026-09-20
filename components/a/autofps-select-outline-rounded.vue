<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp0lmczie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:autofps-select-outline-rounded" /></template>
<style>
.fp0lmczie {
  fill: currentColor;
  d: path("m10.95 9.316l1-2.747h.062l1.038 2.747zM12.005 14q-2.082 0-3.544-1.457T7 9.005T8.457 5.46T11.995 4t3.544 1.457T17 8.996t-1.457 3.542T12.005 14m-1.328-3.954h2.646l.544 1.431q.05.137.152.195q.102.059.235.059q.228 0 .352-.17t.036-.388l-2.277-5.721q-.028-.085-.112-.134t-.175-.049h-.206q-.091 0-.175.049t-.112.134l-2.176 5.76q-.061.179.045.349q.105.17.3.17q.13 0 .22-.062t.14-.179zM4.346 21.5q-.213 0-.356-.144T3.846 21v-3q0-.213.144-.356q.144-.144.357-.144t.356.144t.143.356v3q0 .213-.144.356t-.356.144m3.028-.144q-.143-.144-.143-.356v-3q0-.213.144-.356t.356-.144t.356.144t.144.356v3q0 .213-.144.356q-.144.144-.357.144t-.356-.144m3.385 0q-.143-.144-.143-.356v-3q0-.213.143-.356q.144-.144.357-.144t.356.144t.144.356v3q0 .213-.145.356t-.356.144t-.356-.144m3.741.144q-.213 0-.356-.144T14 21v-3q0-.213.144-.356t.356-.144h5.154q.212 0 .356.144t.144.356v3q0 .213-.144.356t-.356.144z");
}

</style>
