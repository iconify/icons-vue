<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soxbm8c4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-shipping-outline-sharp" /></template>
<style>
.soxbm8c4t {
  fill: currentColor;
  d: path("M3.837 18.353q-.76-.763-.76-1.853H1.692V5H16.54v3.616h2.307l3.462 4.653V16.5h-1.616q0 1.09-.764 1.853t-1.856.762t-1.85-.762t-.76-1.853H8.307q0 1.096-.764 1.856t-1.856.76t-1.852-.763m3.001-.708q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.146-.47M2.692 15.5h.646q.214-.662.87-1.138t1.484-.478q.79 0 1.466.468q.675.467.888 1.148h7.493V6H2.691zm16.53 2.145q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.145-.47M16.538 13.5h4.712l-2.942-3.884h-1.77zm-7.422-2.75");
}

</style>
