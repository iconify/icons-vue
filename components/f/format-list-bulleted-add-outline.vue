<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fedr2ib7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-list-bulleted-add-outline" /></template>
<style>
.fedr2ib7g {
  fill: currentColor;
  d: path("M17.616 20.885h.769v-2.5h2.5v-.77h-2.5v-2.5h-.77v2.5h-2.5v.77h2.5zM18 22q-1.671 0-2.835-1.164Q14 19.67 14 18t1.165-2.835T18 14t2.836 1.165T22 18t-1.164 2.836T18 22M9.616 6.5v-1H20v1zM5.327 19.327q-.547 0-.937-.39T4 18t.39-.937t.937-.39t.937.39t.39.937t-.39.937t-.937.39m0-6q-.547 0-.937-.386Q4 12.556 4 12t.39-.941t.937-.386t.937.386q.39.385.39.941t-.39.941t-.937.386m-.941-6.386Q4 6.556 4 6t.386-.941t.941-.386t.941.386q.386.385.386.941t-.386.941q-.385.386-.941.386t-.941-.386M9.616 18.5v-1h1.901q-.036.25-.036.5t.036.5zm0-6v-1H18q-.944 0-1.79.259q-.847.258-1.566.741z");
}

</style>
