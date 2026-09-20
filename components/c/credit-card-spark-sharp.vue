<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlhhai70i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-card-spark-sharp" /></template>
<style>
.mlhhai70i {
  fill: currentColor;
  d: path("M18.404 21q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.361 1.39 1.358 2.387t2.388 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.388 1.359t-1.358 2.387q-.025.15-.2.15m-6.115-2H3V5h18v6.006q-.238-.127-.479-.224q-.24-.098-.521-.165v-1.81H4v2.385h11.377q-1.529.818-2.492 2.345t-.962 3.367q0 .535.096 1.066t.27 1.03");
}

</style>
