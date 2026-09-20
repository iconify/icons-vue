<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-95ypbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label-outline" /></template>
<style>
.k-95ypbqb {
  fill: currentColor;
  d: path("M4.616 19q-.667 0-1.141-.475T3 17.386V6.615q0-.666.475-1.14T4.615 5h10.212q.384 0 .727.167t.565.46L21 12l-4.88 6.373q-.223.294-.566.46t-.727.167zm0-1h10.211q.154 0 .279-.058t.221-.173L19.75 12l-4.423-5.77q-.096-.114-.221-.172T14.827 6H4.616q-.27 0-.443.173T4 6.616v10.769q0 .269.173.442t.443.173m5.115-6");
}

</style>
