<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leaou1oux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-asterisk-outline-sharp" /></template>
<style>
.leaou1oux {
  fill: currentColor;
  d: path("m12 11l8-5H4zM2 20V4h20v9h-2V8l-8 5l-8-5v10h9v2zm15.875 2.95l-1.75-1l1.15-1.95H15v-2h2.275l-1.15-1.95l1.75-1L19 17l1.125-1.95l1.75 1l-1.15 1.95H23v2h-2.275l1.15 1.95l-1.75 1L19 21z");
}

</style>
