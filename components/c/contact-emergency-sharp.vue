<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx0nnzf8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:contact-emergency-sharp" /></template>
<style>
.zx0nnzf8j {
  fill: currentColor;
  d: path("M1 19.616V4.385h22v15.23zm9.77-6.116q.73-.73.73-1.77t-.73-1.768T9 9.23t-1.77.73t-.73 1.77t.73 1.769t1.77.73t1.77-.73m-7.554 5.116h11.569q-1.05-1.356-2.554-2.178T9 15.616t-3.23.822t-2.554 2.178m14.342-6.924h.884v-1.93l1.668.965l.442-.761L18.884 9l1.668-.965l-.442-.762l-1.668.966V6.308h-.884v1.93l-1.667-.965l-.443.762L17.116 9l-1.668.966l.443.761l1.667-.965z");
}

</style>
