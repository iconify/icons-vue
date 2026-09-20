<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqxe9kryh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-wifi-3-bar-alert-outline" /></template>
<style>
.tqxe9kryh {
  fill: currentColor;
  d: path("M18.018 18.79q-.21-.211-.21-.52t.21-.521t.52-.21t.52.21t.211.52t-.21.52t-.52.211t-.52-.21m.02-2.251v-3.616h1v3.616zM3.186 10.474L1.774 9.062q2.089-1.956 4.721-3.009T12 5t5.506 1.053t4.721 3.009l-1.413 1.413q-1.798-1.684-4.073-2.58T12 7t-4.74.895t-4.073 2.58m7.747 8.091q-.434-.433-.434-1.066t.434-1.066Q11.367 16 12 16t1.066.434t.434 1.066t-.434 1.066Q12.633 19 12 19t-1.066-.434M7.2 14.45l-1.408-1.408q1.264-1.22 2.861-1.872q1.597-.65 3.347-.65q1.292 0 2.497.356q1.205.357 2.274 1.026q-.494.217-.987.533q-.492.315-.863.74q-.669-.325-1.408-.49q-.74-.166-1.513-.166q-1.367 0-2.597.5T7.2 14.45");
}

</style>
