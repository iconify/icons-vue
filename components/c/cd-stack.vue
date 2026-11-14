<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ufeg8fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cd-stack" /></template>
<style>
.p-ufeg8fy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.227 4.227q-.809.809-1.286 1.754q-2.099 1.043-3.019 3.01q-2.954 1.477-3.561 4.793q-.638 3.484 1.867 5.988t5.988 1.867q3.316-.607 4.793-3.561q1.967-.92 3.01-3.019q.945-.477 1.754-1.286Q21.75 11.796 21.75 9t-1.977-4.773T15 2.25t-4.773 1.977M12.5 9q0-2.5 2.5-2.5q1.036 0 1.768.732T17.5 9t-.732 1.768T15 11.5q-2.5 0-2.5-2.5m1.847 7.724q-.18.03-.326.14q-.502.195-1.075.3q-2.71.496-4.658-1.452t-1.452-4.658q.105-.573.3-1.075q.064-.085.101-.184q.027-.069.039-.142q.378-.806 1.012-1.412q-.038.371-.038.759q0 2.796 1.977 4.773T15 15.75q.388 0 .759-.038q-.606.634-1.412 1.012m-9.056-5.486q-.403 3.195 1.937 5.534t5.534 1.937q-1.087 1.138-2.816 1.455q-2.71.496-4.658-1.452t-1.452-4.658q.317-1.729 1.455-2.816");
}

</style>
