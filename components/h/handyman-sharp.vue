<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krecopb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:handyman-sharp" /></template>
<style>
.krecopb3w {
  fill: currentColor;
  d: path("M18.167 20.922q-.136-.053-.267-.183l-4.984-4.966q-.131-.13-.184-.267t-.053-.298t.053-.299q.053-.136.184-.267l1.663-1.663q.13-.131.267-.184t.298-.053t.298.053t.268.184l4.984 4.984q.131.131.184.268q.053.136.053.298t-.053.298t-.184.267l-1.663 1.644q-.131.131-.267.184q-.137.053-.298.053q-.162 0-.299-.053m-12.958.003q-.14-.056-.27-.187L3.28 19.1q-.131-.13-.187-.27t-.056-.301q0-.162.056-.308t.187-.277l5.146-5.146h2.087l.773-.773l-4.24-4.24H5.62L3.096 5.26L5.23 3.127l2.525 2.525v1.425l4.24 4.24l3.016-3.015l-1.844-1.844l1.13-1.131H12.03l-.412-.392l2.839-2.839l.392.392v2.287l1.13-1.13l3.974 3.934q.367.348.544.799q.177.45.177.955q0 .369-.11.717t-.322.658l-2.05-2.048l-1.419 1.419l-1.07-1.07l-4.501 4.503v2.119l-5.127 5.108q-.13.13-.267.186t-.298.056t-.301-.056");
}

</style>
