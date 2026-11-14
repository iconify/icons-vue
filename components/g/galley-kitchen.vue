<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lal3shbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:galley-kitchen" /></template>
<style>
.lal3shbin {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 1.75h-2.75q-3.375 0-3.375 3.375v13.75q0 3.375 3.375 3.375h2.75q3.375 0 3.375-3.375V5.125q0-3.375-3.375-3.375M4.25 8H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h1.75v.5q0 2.25 2.25 2.25T8.75 10V7.5q0-2.25-2.25-2.25T4.25 7.5zm14.375-6.25h.25q3.375 0 3.375 3.375v13.75q0 3.375-3.375 3.375h-.25q-3.375 0-3.375-3.375V5.125q0-3.375 3.375-3.375");
}

</style>
