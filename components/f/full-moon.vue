<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGmHraK7ic" class="li61fhsio"/></defs><use href="#SVGmHraK7ic" class="j71m3fb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:full-moon" /></template>
<style>
.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.li61fhsio {
  d: path("M.23 64c0 35.21 28.54 63.76 63.77 63.76c35.21 0 63.77-28.55 63.77-63.76C127.77 28.78 99.22.23 64 .23S.23 28.78.23 64");
}

</style>
