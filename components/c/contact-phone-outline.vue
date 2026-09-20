<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1ufk1bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-phone-outline" /></template>
<style>
.r1ufk1bio {
  fill: currentColor;
  d: path("M2.616 19.616q-.691 0-1.153-.463T1 18V6q0-.69.463-1.153t1.152-.463h18.77q.69 0 1.153.463T23 6v12q0 .69-.462 1.153t-1.153.463zm12.169-1h6.6q.23 0 .423-.193Q22 18.231 22 18V6q0-.23-.192-.423q-.193-.192-.424-.192H2.616q-.231 0-.424.192T2 6v12q0 .23.192.423t.423.193h.6q1.05-1.356 2.554-2.178T9 15.616t3.23.822t2.555 2.178M10.769 13.5q.731-.73.731-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m7.538 3.923l1.615-1.615l-1.23-1.654h-1.728q-.188-.565-.269-1.078T16.616 12t.08-1.051t.27-1.103h1.726l1.231-1.654l-1.615-1.615q-1.216.992-1.897 2.413q-.68 1.42-.68 3.01t.68 3.01t1.897 2.413M4.55 18.616h8.9q-.87-.95-2.022-1.475q-1.153-.525-2.428-.525t-2.425.525t-2.025 1.475m3.391-5.826q-.441-.442-.441-1.06t.441-1.058T9 10.231t1.059.441t.441 1.059t-.441 1.059q-.442.44-1.059.44t-1.059-.44M12 12");
}

</style>
