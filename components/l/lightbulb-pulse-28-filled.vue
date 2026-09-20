<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="faxazcfnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-pulse-28-filled" /></template>
<style>
.faxazcfnw {
  fill: currentColor;
  d: path("M17.94 23.508A3.25 3.25 0 0 1 14.78 26h-1.56a3.25 3.25 0 0 1-3.16-2.492L9.7 22h8.6zm-5.6-6.704a1.75 1.75 0 0 0 3.268.136l1.616-3.771l.256.45A1.75 1.75 0 0 0 19 14.5h3.292a9 9 0 0 1-2.501 3.39c-.403.339-.68.736-.781 1.158l-.35 1.452H9.34l-.349-1.452c-.101-.422-.378-.82-.781-1.158a9 9 0 0 1-2.501-3.39H9a1.75 1.75 0 0 0 1.645-1.152l.283-.78zM11.01 6.5a.75.75 0 0 1 .702.513l2.375 7.127l2.224-5.186a.75.75 0 0 1 1.34-.076L19.436 12h3.314a.75.75 0 0 1 0 1.5H19a.75.75 0 0 1-.651-.378l-1.253-2.192l-2.406 5.616a.75.75 0 0 1-1.402-.059l-2.32-6.958l-1.263 3.477A.75.75 0 0 1 9 13.5H5.25a.75.75 0 0 1 0-1.5h3.225l1.82-5.006a.75.75 0 0 1 .715-.494M14 2a9 9 0 0 1 9 9h-2.984L18.52 8.382a1.75 1.75 0 0 0-3.076.066l-.052.113l-1.188 2.768l-1.544-4.633a1.75 1.75 0 0 0-3.252-.173l-.053.13L7.775 11H5a9 9 0 0 1 9-9");
}

</style>
