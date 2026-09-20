<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koshk6bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-mail-sharp" /></template>
<style>
.koshk6bpw {
  fill: currentColor;
  d: path("M14.192 11.192h6.616V6.577h-6.616zm3.308-1.134l-2.461-1.712v-.884L17.5 9.173l2.462-1.711v.884zM1 19.616V4.385h22v15.23zm9.77-6.114q.73-.728.73-1.769t-.728-1.771t-1.77-.731t-1.771.728t-.731 1.77t.729 1.771t1.769.73t1.771-.728m-7.553 5.114h11.569q-1.05-1.356-2.554-2.178T9 15.616t-3.23.822t-2.554 2.178");
}

</style>
