<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6dwlublv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:check-circle-unread-outline" /></template>
<style>
.j6dwlublv {
  fill: currentColor;
  d: path("M16.73 7.272Q16 6.543 16 5.502t.729-1.771T18.498 3t1.771.729T21 5.498t-.728 1.771t-1.77.731t-1.771-.728m-8.238 13.02q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51q.709-1.643 1.924-2.859T8.49 3.709T12 3q.662 0 1.291.1q.63.1 1.247.28q-.14.21-.228.45t-.145.49q-.538-.15-1.07-.236Q12.564 4 12 4Q8.65 4 6.325 6.325T4 12t2.325 5.675T12 20t5.675-2.325T20 12q0-.563-.084-1.095q-.085-.532-.235-1.07q.25-.056.487-.154t.451-.22q.181.618.281 1.248T21 12q0 1.868-.708 3.51t-1.923 2.858t-2.857 1.923t-3.509.709t-3.51-.708m2.063-4.384l6.229-6.23q-.25-.097-.477-.221t-.433-.29l-5.313 5.314l-2.85-2.839l-.708.708z");
}

</style>
