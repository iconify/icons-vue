<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joj1m6bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:highlighter-pen" /></template>
<style>
.joj1m6bpk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.8 4.669l.531.531q2.386 2.386 0 4.772l-3.359 3.359q-1.385 1.385-2.77 1.162q-.153.347-.5.694l-.122.122q-.879.879-2.095.599l-1.593-.368q-1.146-.264-1.471-1.395q-.324-1.131.508-1.963l.531-.531q.537-.536 1.074-.711q-.321-1.456 1.135-2.912l3.359-3.359q2.386-2.386 4.772 0M14 18.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h11q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 18.75");
}

</style>
