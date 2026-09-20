<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfyh_dujj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-shipping-outline-rounded" /></template>
<style>
.cfyh_dujj {
  fill: currentColor;
  d: path("M3.837 18.353q-.76-.763-.76-1.853H2.5q-.343 0-.575-.232t-.233-.576V6.616q0-.691.463-1.153T3.308 5h11.615q.667 0 1.141.475t.475 1.14v2h1.5q.383 0 .726.172q.344.172.566.475l2.815 3.79q.081.101.121.222t.04.263v2.155q0 .344-.231.576t-.576.232h-.808q0 1.09-.764 1.853t-1.855.762t-1.852-.762t-.76-1.853H8.309q0 1.096-.764 1.856t-1.856.76t-1.852-.763m3.001-.708q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.146-.47M2.692 15.5h.646q.214-.662.87-1.138t1.484-.478q.79 0 1.466.468q.675.467.888 1.148h7.493V6.616q0-.27-.174-.443Q15.192 6 14.923 6H3.308q-.231 0-.423.192q-.193.193-.193.424zm16.53 2.145q.47-.47.47-1.145t-.47-1.145t-1.145-.47t-1.145.47t-.47 1.145t.47 1.145t1.145.47t1.145-.47M16.538 13.5h4.712L18.5 9.866q-.096-.116-.221-.183T18 9.616h-1.461zm-7.422-2.75");
}

</style>
