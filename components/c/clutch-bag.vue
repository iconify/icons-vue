<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="j08mki2gz"/><path class="z2pkofref"/><path class="d4-uovbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:clutch-bag" /></template>
<style>
.d4-uovbpx {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M8 13s2.5 8.5 4 7s-4-7-4-7m23.258 0s-2.5 8.5-4 7s4-7 4-7");
}

.j08mki2gz {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M7.598 13.736c-.993 3.26-3.588 5.228-5.091 5.228c-.261 0-.507 0-.507-.964c0-1.699 2.78-3.284 5.598-4.264M10 11S0 13 0 18c0 2.043 1.069 2.964 2.507 2.964C5.469 20.964 10 17.059 10 11");
}

.z2pkofref {
  fill: var(--svg-color--a6d388, #a6d388);
  d: path("M33.752 14.969C33.479 12.786 31.457 11 29.257 11H10.743c-2.2 0-4.223 1.786-4.495 3.969L4.495 29.03C4.223 31.214 5.8 33 8 33h24c2.2 0 3.777-1.786 3.505-3.97z");
}

</style>
