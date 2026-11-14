<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep7axkb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:help-contact" /></template>
<style>
.ep7axkb3u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 10.25v.838q-.771.19-1.371.791q-.879.878-.879 2.121v2q0 1.243.879 2.121Q3.507 19 4.75 19t2.121-.879q.879-.878.879-2.121v-2q0-2.598-2.25-2.946v-.804q0-2.692 1.904-4.596T12 3.75t4.596 1.904T18.5 10.25v.804q-2.25.348-2.25 2.946v2q0 1.243.879 2.121q.534.534 1.202.744q-.838 1.385-5.831 1.385q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q6.732 0 7.421-2.82q.819-.178 1.45-.809q.879-.878.879-2.121v-2q0-2.598-2.25-2.946v-.804q0-3.314-2.343-5.657T12 2.25T6.343 4.593T4 10.25");
}

</style>
