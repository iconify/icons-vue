<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc_pn-9fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fast-rewind-outline-rounded" /></template>
<style>
.bc_pn-9fd {
  fill: currentColor;
  d: path("m19.95 16.975l-6.2-4.15q-.225-.15-.337-.362T13.3 12t.113-.462t.337-.363l6.2-4.15q.125-.1.275-.125t.275-.025q.4 0 .7.275t.3.725v8.25q0 .45-.3.725t-.7.275q-.125 0-.275-.025t-.275-.125m-10 0l-6.2-4.15q-.225-.15-.337-.362T3.3 12t.113-.462t.337-.363l6.2-4.15q.125-.1.275-.125t.275-.025q.4 0 .7.275t.3.725v8.25q0 .45-.3.725t-.7.275q-.125 0-.275-.025t-.275-.125M9.5 14.25v-4.5L6.1 12zm10 0v-4.5L16.1 12z");
}

</style>
