<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjo_wjbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lab-profile-sharp" /></template>
<style>
.mjo_wjbji {
  fill: currentColor;
  d: path("M8 12h8v-2H8zm0-4h8V6H8zm12 12.55L14.975 14H4V2h16zM4 22v-6h10l4.6 6z");
}

</style>
