<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qy6mjv50d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eqb" /></template>
<style>
.qy6mjv50d {
  fill: var(--svg-color--4bff00, #4bff00);
  fill-rule: evenodd;
  d: path("M12 18.75a6.75 6.75 0 0 0 1.125-13.404v4.078a2.812 2.812 0 1 1-2.25 0V5.346A6.75 6.75 0 0 0 12 18.75M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

</style>
