<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7n5fbcvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-card-spark" /></template>
<style>
.n7n5fbcvr {
  fill: currentColor;
  d: path("M12.289 19H4.616q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v4.39q-.239-.127-.479-.224T20 10.617v-1.81H4v2.385h11.377q-1.529.818-2.492 2.345t-.962 3.367q0 .535.096 1.066t.27 1.03m6.115 2q-.15 0-.2-.15q-.362-1.39-1.359-2.387t-2.387-1.36q-.15-.05-.15-.2q0-.174.15-.2q1.39-.36 2.387-1.358q.997-.997 1.359-2.387q.05-.15.2-.15q.169 0 .2.15q.362 1.39 1.359 2.387t2.387 1.359q.15.025.15.2q0 .15-.15.2q-1.39.362-2.387 1.359t-1.36 2.387q-.024.15-.2.15");
}

</style>
