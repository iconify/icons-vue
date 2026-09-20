<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc8qu2b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:label" /></template>
<style>
.zc8qu2b_c {
  fill: currentColor;
  d: path("M4.616 19q-.667 0-1.141-.475T3 17.386V6.615q0-.666.475-1.14T4.615 5h10.212q.384 0 .727.167t.565.46L21 12l-4.88 6.373q-.223.294-.566.46t-.727.167z");
}

</style>
