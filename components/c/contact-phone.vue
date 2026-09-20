<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao1k9lu7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-phone" /></template>
<style>
.ao1k9lu7d {
  fill: currentColor;
  d: path("M2.616 19.616q-.691 0-1.153-.463T1 18V6q0-.69.463-1.153t1.152-.463h18.77q.69 0 1.153.463T23 6v12q0 .69-.462 1.153t-1.153.463zm8.153-6.116q.731-.73.731-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m7.538 3.923l1.615-1.615l-1.23-1.654h-1.728q-.188-.565-.269-1.078T16.616 12t.08-1.051t.27-1.103h1.726l1.231-1.654l-1.615-1.615q-1.216.992-1.897 2.413q-.68 1.42-.68 3.01t.68 3.01t1.897 2.413M3.215 18.616h11.57q-1.05-1.356-2.554-2.178T9 15.616t-3.23.822t-2.554 2.178");
}

</style>
