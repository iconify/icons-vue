<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3qg_kbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:broadcast-message" /></template>
<style>
.v3qg_kbci {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.823 8.25H5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T4.25 9v6q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.823l1.027.514l.92 3.908q.017.072.047.139q.031.067.074.127t.097.11t.117.09t.132.064t.142.038t.147.01t.146-.02t.139-.047t.127-.074t.11-.097q.051-.054.09-.117t.064-.132t.038-.142t.01-.147t-.02-.146l-.633-2.691l7.068 3.534q.158.079.335.079q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V4q0-.177-.079-.335q-.067-.134-.18-.232q-.112-.097-.254-.145q-.141-.047-.29-.036q-.149.01-.282.077z");
}

</style>
