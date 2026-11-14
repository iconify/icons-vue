<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyer0lbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:boat-license" /></template>
<style>
.eyer0lbmx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 3.75h10.25q2.123 0 3.624 1.501t1.501 3.624v6.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 15.125v-6.25q0-2.123 1.501-3.624T6.875 3.75m4.375 8.5H6.5q-.199 0-.372.099q-.13.074-.221.192t-.131.262q-.039.144-.02.292t.093.277l2 3.5q.049.086.119.157q.07.07.156.12t.181.075q.096.026.195.026h7q.099 0 .195-.026t.181-.075q.086-.05.156-.12q.07-.071.119-.157l2-3.5q.099-.173.099-.372q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.118l-3.775-5.191q-.053-.072-.12-.129q-.068-.058-.147-.098q-.079-.041-.165-.061q-.086-.021-.175-.021q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146z");
}

</style>
