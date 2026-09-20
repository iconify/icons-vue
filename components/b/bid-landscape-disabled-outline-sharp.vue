<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox5hlv0cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bid-landscape-disabled-outline-sharp" /></template>
<style>
.ox5hlv0cj {
  fill: currentColor;
  d: path("M2.19 2.871L21.13 21.81l-.714.713L17.893 20H4V6.108L1.477 3.585zm7.04 9.118L5 16.218V19h11.892l-3.33-3.33l-.3.33zM5 7.108v7.684l3.842-3.842zM6.17 4H20v13.83l-1-1V9.597l-3.423 3.812l-.713-.714L19 8.096V5H7.17zm6.865 6.866");
}

</style>
