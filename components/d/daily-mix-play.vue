<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc-zhsbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:daily-mix-play" /></template>
<style>
.uc-zhsbgv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 3.75H6.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014H19q1.25 0 1.25 1.25V16q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V6.5q0-2.75-2.75-2.75m-12.5 3h8q1.76 0 3.005 1.245T18.75 11v5q0 1.76-1.245 3.005T14.5 20.25h-8q-1.76 0-3.005-1.245T2.25 16v-5q0-1.76 1.245-3.005T6.5 6.75m4.616 4.381l.727.416q1.133.648 1.133 1.953t-1.133 1.953l-.727.416q-1.125.643-2.246-.008q-1.12-.65-1.12-1.946v-.83q0-1.296 1.12-1.946q1.121-.651 2.246-.008");
}

</style>
