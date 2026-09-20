<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayi7u1b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:household-supplies-sharp" /></template>
<style>
.ayi7u1b5o {
  fill: currentColor;
  d: path("M7.077 20.23v-5.3q0-1.85.621-3.648q.621-1.8 1.977-3.557l-.75.077q-.758.006-1.341-.535Q7 6.727 7 5.957v-.991q0-.816.682-1.35q.681-.533 1.48-.466L18 3.99v2.987l-1.492.162q.311 1.09.79 1.969t1.164 1.361l-.5.866q-.921-.622-1.512-1.725q-.59-1.102-.92-2.393l-2.407.235q.123 1.365.724 2.727t1.445 2.752q.412.685.598 1.435q.187.75.187 1.515v4.35zM8 5.1v.78q0 .45.325.726t.775.225l7.9-.75V4.9l-7.9-.75q-.45-.05-.775.225T8 5.1");
}

</style>
