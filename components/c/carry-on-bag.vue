<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvo862ein"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:carry-on-bag" /></template>
<style>
.qvo862ein {
  fill: currentColor;
  d: path("M13.909 20.589q-.447-.45-.447-1.091t.449-1.09q.45-.446 1.091-.446t1.09.449t.447 1.091t-.45 1.09q-.45.447-1.091.447t-1.09-.45M8.617 20q-.667 0-1.141-.475T7 18.386v-8.77q0-.666.475-1.14T8.615 8H9.5v12zm1.769 0V8H14V4h-.615q-.402 0-.701-.299q-.3-.299-.3-.701H15v14.077q-1.02 0-1.721.707t-.702 1.716q0 .134.009.25t.05.25z");
}

</style>
