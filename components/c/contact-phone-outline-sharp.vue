<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="va80oqb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-phone-outline-sharp" /></template>
<style>
.va80oqb_z {
  fill: currentColor;
  d: path("m18.308 17.423l1.615-1.615l-1.23-1.654h-1.728q-.188-.566-.269-1.078T16.616 12t.08-1.051t.27-1.103h1.726l1.231-1.654l-1.615-1.615q-1.216.992-1.897 2.413q-.68 1.42-.68 3.01t.68 3.01t1.897 2.413M1 19.616V4.385h22v15.23zm13.785-1H22V5.385H2v13.23h1.216q1.05-1.355 2.553-2.177T9 15.616t3.23.822t2.555 2.178M10.769 13.5q.731-.73.731-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m-6.22 5.116h8.9q-.87-.95-2.022-1.475q-1.153-.525-2.428-.525t-2.425.525t-2.025 1.475m3.391-5.826q-.441-.442-.441-1.06t.441-1.058T9 10.231t1.059.441t.441 1.059t-.441 1.059q-.442.44-1.059.44t-1.059-.44M12 12");
}

</style>
