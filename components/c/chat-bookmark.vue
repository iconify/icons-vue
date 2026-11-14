<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcm158bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-bookmark" /></template>
<style>
.lcm158bsx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 2.75Q3.25 2.75 3.25 6v8q0 3.122 3 3.245V20q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H17.5q3.25 0 3.25-3.25V6q0-3.25-3.25-3.25zm2 2.75h7q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.24 0-.436-.14L12 12.172L8.936 14.36q-.06.043-.128.074q-.067.03-.139.047q-.072.016-.146.019q-.073.002-.146-.01t-.142-.038t-.132-.066q-.063-.039-.117-.089q-.053-.051-.096-.111q-.14-.196-.14-.436v-7.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8.5 5.5");
}

</style>
