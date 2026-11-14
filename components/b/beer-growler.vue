<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p779p9bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:beer-growler" /></template>
<style>
.p779p9bwp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 1.75h5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v.75H16q2.75 0 2.75 2.75v13.5q0 2.25-2.25 2.25h-9q-2.25 0-2.25-2.25v-9q0-2.093 2.447-4.275Q8.75 5.285 8.75 5V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m7.75 5.417V6q0-1.25-1.25-1.25h-.75V5q0 .285 1.053 1.225q.531.473.947.942m-7 4.583q-2.5 0-2.5 2.5v1.5q0 2.5 2.5 2.5h3.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768t-1.768-.732z");
}

</style>
