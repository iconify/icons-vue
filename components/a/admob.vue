<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient x1="50%" y1="0%" x2="50%" y2="99.302%" id="ssvg-id-admoba"><stop offset="0%" class="nku9chaxw"/><stop offset="100%" class="d6o1i3elf"/></linearGradient></defs><path class="n8vg3p7ta"/><path class="olnh5u97m"/><path fill="url(#ssvg-id-admoba)" class="cjgd3qbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:admob" /></template>
<style>
.cjgd3qbcz {
  d: path("M256 81.606v80.447l-81.329-80.447z");
}

.d6o1i3elf {
  stop-color: var(--svg-color--404040, #404040);
  stop-opacity: 0;
}

.n8vg3p7ta {
  d: path("M127.983 174.982c-25.785 0-46.688-20.903-46.688-46.688c0-25.786 20.903-46.688 46.688-46.688H256L175.138 0h-47.155C57.3 0 0 57.3 0 127.982c0 70.684 57.3 127.984 127.983 127.984v-80.984z");
  fill: var(--svg-color--de564a, #DE564A);
}

.nku9chaxw {
  stop-color: var(--svg-color--404040, #404040);
  stop-opacity: 0.3;
}

.olnh5u97m {
  fill: var(--svg-color--465b65, #465B65);
  d: path("M174.671 255.966H256V81.606h-81.329z");
}

</style>
