<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1f9ifbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gbyte" /></template>
<style>
.d1f9ifbha {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 21a9 9 0 0 0 9-9a9 9 0 0 0-9-9a9 9 0 0 0-9 9a9 9 0 0 0 9 9");
}

</style>
