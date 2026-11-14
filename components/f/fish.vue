<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1aw-ccav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fish" /></template>
<style>
.a1aw-ccav {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.329 10.891Q9.834 5.75 14.5 5.75q5.707 0 7.712 6.013q.038.115.038.237t-.038.237Q20.207 18.25 14.5 18.25q-4.666 0-8.172-5.141q-.206.329-.535.658l-.763.764q-.908.906-2.093.415q-1.185-.49-1.187-1.774v-2.345q.002-1.283 1.187-1.773q1.185-.491 2.093.416l.763.763h.001q.328.329.535.658M17.01 9.75H17q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
