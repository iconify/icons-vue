<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tud6a6bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-mail-rounded" /></template>
<style>
.tud6a6bur {
  fill: currentColor;
  d: path("M2.616 19.616q-.691 0-1.153-.463T1 18V6q0-.69.463-1.153t1.152-.463h18.77q.69 0 1.153.463T23 6v12q0 .69-.462 1.153t-1.153.463zm8.153-6.116q.731-.73.731-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m-7.554 5.116h11.569q-1.05-1.356-2.554-2.178T9 15.616t-3.23.822t-2.554 2.178M15 11.192h5q.348 0 .578-.23t.23-.577v-3q0-.348-.23-.578T20 6.577h-5q-.348 0-.578.23t-.23.577v3q0 .349.23.578q.23.23.578.23m2.5-2.019l1.889-1.32q.18-.13.377-.018q.196.113.196.324q0 .064-.156.293l-1.847 1.282q-.217.143-.459.143t-.46-.143l-1.846-1.282q-.044-.044-.155-.293q0-.211.196-.324q.196-.112.377.019z");
}

</style>
