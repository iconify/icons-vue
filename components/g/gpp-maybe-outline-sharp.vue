<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbyb92b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gpp-maybe-outline-sharp" /></template>
<style>
.rbyb92b5h {
  fill: currentColor;
  d: path("M12.434 15.049q.182-.182.182-.433q0-.252-.182-.434T12 14t-.434.182t-.182.433t.182.434t.434.182t.434-.182m-.934-2.626h1V7.769h-1zm.5 8.539q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963m0-1.062q2.6-.825 4.3-3.3t1.7-5.5V6.375l-6-2.23l-6 2.23V11.1q0 3.025 1.7 5.5t4.3 3.3m0-7.88");
}

</style>
