<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpxy2l7pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-three-eighth-fill" /></template>
<style>
.fpxy2l7pm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12ZM16.9498 7.0502C15.6841 5.7846 13.9328 5 12 5C11.4477 5 11 5.4477 11 6L11 12C11 12.2652 11.1054 12.5196 11.2929 12.7071L15.5355 16.9497C15.723 17.1372 15.9774 17.2426 16.2426 17.2426C16.5078 17.2426 16.7621 17.1373 16.9497 16.9497C18.2625 15.637 19 13.8565 19 12C19 10.0672 18.2154 8.3159 16.9498 7.0502Z");
}

</style>
