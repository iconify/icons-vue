<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-zeihb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-phone-sharp" /></template>
<style>
.f-zeihb5a {
  fill: currentColor;
  d: path("M1 19.616V4.385h22v15.23zm9.77-6.116q.73-.73.73-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m-7.554 5.116h11.569q-1.05-1.356-2.554-2.178T9 15.616t-3.23.822t-2.554 2.178m15.092-1.193l1.615-1.615l-1.23-1.654h-1.727q-.189-.565-.27-1.078T16.616 12t.08-1.051t.27-1.103h1.726l1.231-1.654l-1.615-1.615q-1.216.992-1.897 2.413q-.68 1.42-.68 3.01t.68 3.01t1.897 2.413");
}

</style>
