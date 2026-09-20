<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlpl6t05c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blood-pressure-outline-sharp" /></template>
<style>
.vlpl6t05c {
  fill: currentColor;
  d: path("M3 9.116v-2.5q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v5.5h-1v-5.5q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v2.5zM10.944 19H4.615q-.69 0-1.153-.462T3 17.384v-2.5h1v2.5q0 .231.192.424t.423.192h6.076q.055.275.109.516q.054.24.144.484m3.22.836Q13 18.67 13 17t1.165-2.835T17 13t2.836 1.165T21 17t-1.164 2.836T17 21t-2.835-1.164m3.035-2.49l1.929-1.929l-.546-.546l-1.93 1.929zM3 12.5v-1h2.292L7 14.89l3.83-7.717h.295l2.296 4.554l-.43.315q-.21.156-.387.339L10.98 9.135l-3.856 7.711h-.288L4.683 12.5z");
}

</style>
