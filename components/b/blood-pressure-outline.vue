<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_mnc4b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:blood-pressure-outline" /></template>
<style>
.t_mnc4b3q {
  fill: currentColor;
  d: path("M3 9.116v-2.5q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v5.5h-1v-5.5q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v2.5zM7 16.5q-.16 0-.275-.06q-.115-.061-.183-.202L4.682 12.5H3v-1h2q.14 0 .256.07t.182.21L7 14.886l3.542-7.104q.067-.115.192-.173T11 7.55t.256.058t.183.173l1.982 3.946l-.43.315q-.21.156-.387.339L10.98 9.135l-3.542 7.104q-.068.14-.183.2Q7.14 16.5 7 16.5m3.944 2.5H4.615q-.69 0-1.153-.462T3 17.384v-2.5h1v2.5q0 .231.192.424t.423.192h6.076q.055.275.109.516q.054.24.144.484m3.22.836Q13 18.67 13 17t1.165-2.835T17 13t2.836 1.165T21 17t-1.164 2.836T17 21t-2.835-1.164m3.035-2.49l1.929-1.929l-.546-.546l-1.93 1.929z");
}

</style>
