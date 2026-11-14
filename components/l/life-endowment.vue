<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_0kxwaax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:life-endowment" /></template>
<style>
.s_0kxwaax {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.563 7.658q.379-1.036 1.219-1.876Q14.314 4.25 16.5 4.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2.186-1.532 3.718q-1.262 1.262-2.968 1.484v2.807q6 .148 6 2.741q0 .991-.877 1.625q.877.634.877 1.625q0 2.75-6.75 2.75T5.25 19q0-.991.877-1.625q-.877-.634-.877-1.625q0-2.593 6-2.741v-1.307q-1.706-.222-2.968-1.484Q6.75 8.686 6.75 6.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q2.186 0 3.718 1.532q.183.184.345.376");
}

</style>
