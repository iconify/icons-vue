<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhvxi3hxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-dot-fill" /></template>
<style>
.yhvxi3hxb {
  fill: currentColor;
  d: path("M14.315 4.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114M13.432 10H10c-.468 0-.98-.395-1.293-.707l-5-5.001A3 3 0 0 1 5 4h6a.998.998 0 0 1 .99 1.141a6 6 0 0 0 .25 2.779A6 6 0 0 0 13.432 10m2.725-3.222a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556M15 12c.26 0 .51-.102.697-.283c.981.489 2.083.778 3.184.739a4.8 4.8 0 0 0 1.725-.375A.997.997 0 0 1 22 13v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V7c0-.448.099-.889.292-1.293l5.001 5C8.008 11.422 8.961 12 10 12Z");
}

</style>
