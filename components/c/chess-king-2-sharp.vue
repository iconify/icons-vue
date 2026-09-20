<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="few93lbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chess-king-2-sharp" /></template>
<style>
.few93lbeb {
  fill: currentColor;
  d: path("M13 22v-8.875q0-.5.038-1.012t.412-.863q1.1-1.05 2.513-1.65T19 9q1.65 0 2.825 1.175T23 13v9zM1 22v-9q0-1.65 1.175-2.825T5 9t3.088.625t2.537 1.7q.35.35.363.825t.012.975V22zM11 7.15V6H8V4h3V1h2v3h3v2h-3v1.125q.475.125.875.35t.75.525q-.725.35-1.388.825T12 9.875q-.575-.575-1.237-1.05T9.375 8q.35-.3.763-.513T11 7.15");
}

</style>
