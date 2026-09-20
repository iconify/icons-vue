<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg2zk1ezw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:http" /></template>
<style>
.zg2zk1ezw {
  fill: currentColor;
  d: path("M1.73 14.692V9.308h.886v2H5.23v-2h.885v5.384H5.23v-2.5H2.616v2.5zm7.27 0v-4.5H7.308v-.884h4.269v.884H9.885v4.5zm5.116 0v-4.5h-1.693v-.884h4.27v.884H15v4.5zm3.769 0V9.308h2.884q.6 0 1.05.45t.45 1.05v.384q0 .6-.45 1.05t-1.05.45h-2v2zm.884-2.884h2q.231 0 .423-.192q.193-.193.193-.424v-.384q0-.231-.193-.423q-.192-.193-.423-.193h-2z");
}

</style>
