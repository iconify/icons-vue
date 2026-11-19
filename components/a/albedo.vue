<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot_vxybpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:albedo" /></template>
<style>
.ot_vxybpj {
  fill: var(--svg-color--0691b7, #0691b7);
  d: path("M12.376 3h-.752L4.013 20.99l.023.01h2.03l1.524-3.6a15.03 15.03 0 0 0 9.75-.05L18.883 21h1.08l.023-.01Zm.015 14.507a14.3 14.3 0 0 1-4.535-.737l4.62-10.917l4.598 10.869c-1.507.52-3.09.785-4.683.785");
}

</style>
