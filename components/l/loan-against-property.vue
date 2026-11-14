<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzlt7y3ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:loan-against-property" /></template>
<style>
.qzlt7y3ku {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.104 9.412q-.854.746-.854 1.881v7.456q0 2.5 2.5 2.5h7.448Q12 19.873 12 18q0-2.071 1.464-3.536Q14.929 13 17 13h2q.937 0 1.75.3v-2.006q0-1.135-.854-1.881L18.75 8.41V4q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 3.25h-2q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T15.25 4v1.347l-1.604-1.404Q12 2.504 10.354 3.944zM17.25 4.75v2.347l-.5-.437V4.75zm-.25 9.5q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906M17 17q1 0 1 1t-1 1t-1-1t1-1");
}

</style>
