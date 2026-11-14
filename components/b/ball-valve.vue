<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehzm1kbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-valve" /></template>
<style>
.ehzm1kbub {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 8.798q1.697.224 2.962 1.49q.324.324.58.676q.622-.714 1.958-.714h1.5q1.036 0 1.768.732t.732 1.768v2.5q0 1.036-.732 1.768t-1.768.732h-1.5q-1.336 0-1.958-.714q-.256.352-.58.676Q14.175 19.25 12 19.25t-3.712-1.538q-.382-.381-.668-.801q-.049.054-.102.107q-.732.732-1.768.732h-1.5q-2.5 0-2.5-2.5v-2.5q0-2.5 2.5-2.5h1.5q1.036 0 1.768.732q.053.053.102.107q.286-.42.668-.801q1.265-1.266 2.962-1.49V5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 4.25h7q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T19 5.75h-6.25z");
}

</style>
