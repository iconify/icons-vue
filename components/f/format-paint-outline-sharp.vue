<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_ixjk1so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-paint-outline-sharp" /></template>
<style>
.w_ixjk1so {
  fill: currentColor;
  d: path("M9 22v-6H4V7q0-1.65 1.175-2.825T8 3h12v13h-5v6zM6 10h12V5h-1v4h-2V5h-1v2h-2V5H8q-.825 0-1.412.588T6 7zm0 4h12v-2H6zm0 0v-2z");
}

</style>
