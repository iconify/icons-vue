<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5e6xwbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-mail-outline-sharp" /></template>
<style>
.w5e6xwbiq {
  fill: currentColor;
  d: path("M14.192 11.192h6.616V6.577h-6.616zm3.308-1.134l-2.461-1.712v-.884L17.5 9.173l2.462-1.711v.884zM1 19.616V4.385h22v15.23zm13.785-1H22V5.385H2v13.23h1.216q1.05-1.355 2.553-2.177T9 15.616t3.23.822t2.555 2.178M10.769 13.5q.731-.73.731-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m-6.22 5.116h8.9q-.87-.95-2.022-1.475q-1.153-.525-2.428-.525t-2.425.525t-2.025 1.475m3.391-5.826q-.441-.442-.441-1.06t.441-1.058T9 10.231t1.059.441t.441 1.059t-.441 1.059q-.442.44-1.059.44t-1.059-.44M12 12");
}

</style>
