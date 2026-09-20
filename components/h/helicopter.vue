<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glnplibzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:helicopter" /></template>
<style>
.glnplibzz {
  fill: currentColor;
  d: path("M10.077 13.462V7.154q-2.885 0-4.596 1.904T3.769 13.46zm2.673 6.769H4v-1h8.75zm1.712-2.385H4.385q-.667 0-1.141-.474q-.475-.475-.475-1.141v-2.77q0-2.926 2.008-5.117t5.3-2.19h4.385V10h4.884l.885-2h1v5.98l-6.77.705zM18.75 4.77H4v-1h14.75z");
}

</style>
