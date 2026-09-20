<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj-bz14fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drive-fusiontable-outline-sharp" /></template>
<style>
.yj-bz14fi {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-3.78V19h14V9.596L13.242 16l-4.011-4.011zm0-1.428l4.23-4.23l3.99 3.988L19 8.096V5H5zm0-5.196v-1.5v6.454v-3.988v5.657v-4.23V16zm0 5.196V5v9.55v-3.988zm0 1.427v-4.23V16V9.596V19z");
}

</style>
