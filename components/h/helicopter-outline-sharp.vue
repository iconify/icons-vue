<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eep-22bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:helicopter-outline-sharp" /></template>
<style>
.eep-22bqd {
  fill: currentColor;
  d: path("M10.077 13.462V7.154q-2.885 0-4.596 1.904T3.769 13.46zm3.385 3.384V7.154h-2.385v7.308H3.769v2.384zm1-3.161l5.769-.6V11h-5.77zM12.75 20.23H4v-1h8.75zm1.712-2.385H2.769v-4.384q0-2.927 2.008-5.118q2.007-2.19 5.3-2.19h4.385V10h4.884l.885-2h1v5.98l-6.77.705zM18.75 4.77H4v-1h14.75zm-4.288 8.916V11zm-1 3.161");
}

</style>
