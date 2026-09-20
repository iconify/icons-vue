<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itix9ibzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:audio-capture-outline" /></template>
<style>
.itix9ibzc {
  fill: currentColor;
  d: path("M3 20.077v-8.02h1v5.587l1.65-1.663h2.12V17H6.076zM16.23 17v-1.02h3.155q.269 0 .442-.172q.173-.173.173-.442v-3.308h1v3.327q0 .69-.462 1.153T19.385 17zm-4.73-2.192V5.942h1v8.866zm-3.788-1.962V7.904h1v4.942zm7.557-1V8.885h1v2.961zM3 7.942V4.615q0-.69.463-1.153T4.615 3H7.77v1H4.616q-.27 0-.443.173T4 4.616v3.326zm17 0V4.615q0-.269-.173-.442T19.385 4H16.23V3h3.153q.691 0 1.154.463T21 4.616v3.326z");
}

</style>
