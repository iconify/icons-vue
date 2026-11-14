<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4de243_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diary-lock" /></template>
<style>
.v4de243_z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75H8q-.182 0-.359.013q.064.013.124.036q.061.023.117.056t.105.075t.091.092t.074.107t.054.117t.033.125t.011.129v19q0 .065-.011.129t-.033.125t-.054.117t-.074.107t-.091.092t-.105.075t-.117.056q-.06.023-.124.036q.177.013.359.013h8q1.76 0 3.005-1.245T20.25 18V6q0-1.76-1.245-3.005T16 1.75M7.177 22.177q-.096-.046-.175-.116q-.08-.071-.136-.161t-.087-.192q-.029-.102-.029-.208v-19q0-.106.029-.208t.087-.192q.056-.09.136-.161q.079-.07.175-.116q-1.239.229-2.182 1.172Q3.75 4.24 3.75 6v12q0 1.76 1.245 3.005q.943.943 2.182 1.172M12.75 10.75V10q0-.75.75-.75t.75.75v.75zm3 .328q.275.162.518.404q.732.732.732 1.768v1q0 1.036-.732 1.768t-1.768.732h-2q-2.5 0-2.5-2.5v-1q0-1.768 1.25-2.286V10q0-2.25 2.25-2.25T15.75 10z");
}

</style>
