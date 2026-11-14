<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5e64r8uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blood-drop" /></template>
<style>
.w5e64r8uz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.49 2.45q-.021.019-.04.04q-6.7 7.215-6.7 12.01q0 3.003 2.123 5.127T12 21.75t5.127-2.123q2.123-2.124 2.123-5.127q0-4.795-6.7-12.01q-.102-.11-.238-.172q-.135-.062-.284-.067t-.289.046t-.249.153m.51 14.8q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-3.75 0-3.75-3.75q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 14.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 2.25 2.25 2.25");
}

</style>
