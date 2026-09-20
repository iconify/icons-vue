<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbs5_m48k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-phone-rounded" /></template>
<style>
.sbs5_m48k {
  fill: currentColor;
  d: path("M2.616 19.616q-.691 0-1.153-.463T1 18V6q0-.69.463-1.153t1.152-.463h18.77q.69 0 1.153.463T23 6v12q0 .69-.462 1.153t-1.153.463zm8.153-6.116q.731-.73.731-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m-7.554 5.116h11.569q-1.05-1.356-2.554-2.178T9 15.616t-3.23.822t-2.554 2.178M16.616 12q0-.563.08-1.051t.27-1.103h1.322q.193 0 .354-.08q.162-.082.293-.243l.579-.765q.186-.242.161-.54t-.242-.516l-.566-.565q-.236-.237-.56-.24q-.322-.003-.565.234q-.978.961-1.495 2.226q-.516 1.264-.516 2.643t.516 2.643q.517 1.265 1.495 2.226q.243.237.566.234t.56-.24l.565-.565q.217-.217.242-.515t-.161-.54l-.58-.766q-.13-.161-.292-.242t-.353-.081h-1.324q-.188-.565-.269-1.078T16.616 12");
}

</style>
