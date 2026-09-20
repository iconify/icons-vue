<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svlyaobde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:detector-co-sharp" /></template>
<style>
.svlyaobde {
  fill: currentColor;
  d: path("M8.56 14.02q-.416 0-.709-.292t-.293-.707t.29-.709t.708-.293t.709.291t.293.707t-.291.709t-.707.293m3.462 3q-.416 0-.71-.29t-.293-.707t.291-.71t.707-.293t.709.291t.293.707t-.29.709t-.707.293m-3.462 3q-.416 0-.709-.29t-.293-.707t.29-.71t.708-.293t.709.291t.293.707t-.291.709t-.707.293m6.195-6.29q-.293-.292-.293-.707t.29-.71t.707-.293t.71.291t.293.707t-.291.709t-.707.293t-.71-.29m.04 6q-.294-.292-.294-.707t.291-.71t.707-.293t.709.291t.293.707t-.291.709t-.707.293t-.709-.29m4.113-2.71q-.416 0-.709-.29q-.293-.292-.293-.707t.29-.71t.708-.293t.708.291t.294.707t-.291.709t-.707.293m-13.788 0q-.416 0-.71-.29t-.293-.707t.291-.71t.707-.293t.709.291t.293.707t-.29.709q-.292.293-.707.293m2.405-9.48l.646 1.769h7.662l.646-1.77zm-.092 2.769l-.97-2.77H4V3.77h16v3.77h-2.461l-1.074 2.769z");
}

</style>
