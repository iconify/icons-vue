<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_cx2t86h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-2-edit-outline-sharp" /></template>
<style>
.q_cx2t86h {
  fill: currentColor;
  d: path("M11 11V4h11v7zm-9 9v-7h10v7zm0-9V4h7v7zm11-2h7V6h-7zm-9 9h6v-3H4zm0-9h3V6H4zm10 13v-3.075l6.575-6.55l3.075 3.05L17.075 22zm7.5-6.575l-.925-.925zm-6 5.075h.95l3.025-3.05l-.45-.475l-.475-.45l-3.05 3.025zm3.525-3.525l-.475-.45l.925.925z");
}

</style>
