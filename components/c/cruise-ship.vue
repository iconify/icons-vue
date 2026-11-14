<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubwf90k0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cruise-ship" /></template>
<style>
.ubwf90k0o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 7.25h2.5q2.5 0 2.5 2.5v2.5q0 .564-.127 1H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .15-.058.288l-2.5 6q-.042.103-.113.189q-.071.085-.163.147t-.199.094q-.106.032-.217.032h-13q-.111 0-.217-.032q-.107-.032-.199-.094t-.163-.147q-.071-.086-.113-.189l-2.5-6q-.029-.068-.043-.14q-.015-.073-.015-.146q0-.074.014-.147q.014-.072.042-.141t.07-.129q.04-.062.093-.114q.052-.053.113-.094t.13-.069q.138-.058.288-.058h3.377q-.127-.436-.127-1v-2.5q0-2.5 2.5-2.5h2.5V4.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13q.028.068.043.141t.014.146z");
}

</style>
