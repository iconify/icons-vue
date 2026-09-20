<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfk7kv89e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mail-asterisk-sharp" /></template>
<style>
.pfk7kv89e {
  fill: currentColor;
  d: path("m17.875 22.95l-1.75-1l1.15-1.95H15v-2h2.275l-1.15-1.95l1.75-1L19 17l1.125-1.95l1.75 1l-1.15 1.95H23v2h-2.275l1.15 1.95l-1.75 1L19 21zM2 20V4h20v9.775q-.65-.375-1.412-.587T19 12.975q-2.5 0-4.262 1.763T12.975 19q0 .275.013.513t.062.487zm10-7l8-5V6l-8 5l-8-5v2z");
}

</style>
