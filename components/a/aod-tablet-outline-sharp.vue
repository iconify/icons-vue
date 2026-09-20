<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhii_onpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:aod-tablet-outline-sharp" /></template>
<style>
.jhii_onpi {
  fill: currentColor;
  d: path("M1 20V4h22v16zM4 6H3v12h1zm2 12h12V6H6zM20 6v12h1V6zm0 0h1zM4 6H3zm4 5.5V10h8v1.5zm1 3V13h6v1.5z");
}

</style>
