<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0oa0xb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fertile-sharp" /></template>
<style>
.h0oa0xb5i {
  fill: currentColor;
  d: path("M8.493 20.291q-1.643-.708-2.859-1.923T3.709 15.51T3 12V4.5l5.275 3.967q.852-1.31 1.791-2.55q.94-1.24 1.934-2.398q.894 1.039 1.842 2.288t1.858 2.66L21 4.5V12q0 1.868-.708 3.51t-1.924 2.858t-2.856 1.923t-3.509.709t-3.51-.709");
}

</style>
