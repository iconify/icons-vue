<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqihm95pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:image-not-supported-outline-sharp" /></template>
<style>
.iqihm95pz {
  fill: currentColor;
  d: path("M20.11 21.53L18.579 20H4V5.421L2.47 3.885l.707-.708l17.646 17.646l-.713.708ZM5 19h12.579l-2.5-2.5H7l2.5-3.308l1.885 2.283l1.138-1.53L5 6.42V19Zm15-1.825l-1-1V5H7.825l-1-1H20v13.175Zm-6.525-6.525Zm-2.163 2.083Z");
}

</style>
