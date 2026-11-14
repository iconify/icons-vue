<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut4ta04hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:amphora" /></template>
<style>
.ut4ta04hl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 2.25h4q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v1.037q1.678.171 2.557 1.149q1.08 1.199.709 3.297q1.28 2.46.205 6.223q-.993 3.31-5.771 6.894q-.048.036-.102.064t-.111.048q-.057.019-.117.028t-.12.01q-.06 0-.12-.01q-.06-.009-.117-.028t-.111-.048q-.054-.028-.102-.064q-4.778-3.584-5.768-6.884q-1.077-3.769.202-6.23q-.371-2.1.709-3.3q.879-.978 2.557-1.149V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m6.443 4.329q-.097-.219-.25-.39q-.441-.489-1.36-.631q.912.451 1.61 1.021M9.167 5.558q-.919.142-1.36.631q-.153.171-.25.391q.697-.571 1.61-1.022");
}

</style>
