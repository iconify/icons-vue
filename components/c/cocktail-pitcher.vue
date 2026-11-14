<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ai31b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cocktail-pitcher" /></template>
<style>
.t4ai31b_p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 5.812V8q0 .529.73 1.75h3.02q2.75 0 2.75 2.75V15q0 2.75-2.75 2.75h-.75v1.75q0 2.75-2.75 2.75H7q-2.75 0-2.75-2.75v-4q0-2.214 1.931-5.204q.87-1.348 1.032-2.022L4.97 6.03q-.106-.105-.163-.243T4.75 5.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h8.151l1.719-2.657q.04-.062.092-.115q.051-.053.112-.095t.129-.072q.068-.029.14-.044q.072-.016.146-.017t.146.012q.073.014.142.041t.13.067q.062.04.115.092q.053.051.095.112t.072.129t.044.14q.016.072.017.146t-.012.146t-.041.142q-.027.068-.067.13zm3 10.438h.75q1.25 0 1.25-1.25v-2.5q0-1.25-1.25-1.25h-2.103q1.353 2.397 1.353 4.25z");
}

</style>
