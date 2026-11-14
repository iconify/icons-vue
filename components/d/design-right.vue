<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnzjoacak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:design-right" /></template>
<style>
.tnzjoacak {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.056 2.212l6.5 3.453q.28.148.494.337q-.213-.015-.402.086L11 10.151L3.352 6.088q-.189-.101-.402-.086q.214-.188.494-.337l6.5-3.453q1.056-.562 2.112 0m-1.806 9.239L2.648 7.412q-.11-.058-.196-.15q-.085-.091-.136-.205q-.066.278-.066.595v7.196q0 1.352 1.194 1.987l6.5 3.453q.243.129.486.199q-.087-.102-.134-.227q-.046-.126-.046-.26zm9.102-4.039q.11-.058.196-.15q.085-.091.136-.205q.066.278.066.595V13.3Q18.937 13 18 13q-2.071 0-3.536 1.464Q13 15.929 13 18q0 .878.263 1.647l-1.207.641q-.243.129-.486.199q.087-.102.134-.227q.046-.126.046-.26v-8.549zM14.25 18q0-3.75 3.75-3.75T21.75 18T18 21.75T14.25 18m1.5 0q0 2.25 2.25 2.25T20.25 18T18 15.75T15.75 18M18 17q.117 0 .22.014l-1.18.627Q17.2 17 18 17");
}

</style>
