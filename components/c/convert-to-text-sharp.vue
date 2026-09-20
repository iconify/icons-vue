<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofjy2xb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:convert-to-text-sharp" /></template>
<style>
.ofjy2xb9m {
  fill: currentColor;
  d: path("M2 22v-2h2.55q-1.2-.575-1.937-1.7t-.738-2.55q0-1.975 1.388-3.363T6.625 11v2q-1.125 0-1.937.8t-.813 1.95q0 .975.6 1.725t1.525.95V16h2v6zM7 9h10V7H7zm3 12v-4h4v-2h-4v-2h7v-2h-7V9H3V3h18v18z");
}

</style>
