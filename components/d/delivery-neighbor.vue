<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibvuljb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:delivery-neighbor" /></template>
<style>
.ibvuljb9u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.109 7.054q-.609.649-.609 1.539V11.5q0 1.394.863 1.924q.607-.174 1.387-.174h4.5q.78 0 1.387.174q.863-.53.863-1.924V8.593q0-.89-.609-1.539l-2.25-2.4q-.667-.711-1.641-.711t-1.641.711zm-1.859 3.294V19q0 2.25-2.25 2.25H7.25q2.25 0 2.25-2.25v-3.5q0-2.25-2.25-2.25h-.5q-2.25 0-2.25 2.25V19q0 2.25 2.25 2.25H4q-2.25 0-2.25-2.25v-8.652q0-.897.617-1.548l3-3.167Q6.032 4.931 7 4.931t1.634.702L11.633 8.8q.617.651.617 1.548m8 4.152h-4.5q-2.25 0-2.25 2.25v3.5q0 2.25 2.25 2.25h4.5q2.25 0 2.25-2.25v-3.5q0-2.25-2.25-2.25m-3 3.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2h1.5q.75 0 .75.75v3.5q0 .75-.75.75h-4.5q-.75 0-.75-.75v-3.5q0-.75.75-.75h1.5z");
}

</style>
