<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej1yqz-1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-pedal" /></template>
<style>
.ej1yqz-1u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.346 14.906L3.97 9.53q-.038-.037-.07-.08q-1.691-2.255.302-4.248T8.45 4.9q.043.032.08.07l9.781 9.78h.189q2.75 0 2.75 2.75t-2.75 2.75h-8q-2.75 0-2.75-2.75q0-2.095 1.596-2.594m6.843-.156l-8.68-8.68q-1.191-.863-2.246.193q-1.056 1.055-.193 2.246l6.241 6.241zM6.26 6.5h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T6.25 8h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T6.26 6.5");
}

</style>
