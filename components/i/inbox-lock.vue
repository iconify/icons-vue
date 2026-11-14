<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anm23lo6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:inbox-lock" /></template>
<style>
.anm23lo6g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 5.25h2v-.5q0-.414-.293-.707T12 3.75q-1 0-1 1zm3.5.328q.275.162.518.404q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-2.5q-2.5 0-2.5-2.5v-1q0-1.768 1.25-2.286V4.75q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 4.75zM3 11.25h5q.097 0 .191.025q.094.024.179.072t.154.116t.119.151l1.282 2.136h4.15l1.282-2.136q.05-.083.119-.151q.07-.068.154-.116q.085-.048.179-.072q.094-.025.191-.025h5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v6q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75v-6q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T3 11.25");
}

</style>
