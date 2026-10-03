<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="orqaogb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-message-sharp-fill" /></template>
<style>
.orqaogb9u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.7234 19.8057L5.4389 21.8985C4.8104 22.2055 4.0689 21.7889 4.0043 21.0924L3.6081 16.825C1.9807 15.2413 1 13.081 1 11C1 6.1011 6.1264 2 12 2C17.8736 2 23 6.1011 23 11C23 15.8989 17.8736 20 12 20C11.2503 20 10.4661 19.9328 9.7234 19.8057ZM9.882 7.9042L10.593 12.5685L12.5701 12.2671L11.8591 7.6028ZM13.8363 7.3014L14.5473 11.9657L16.5244 11.6643L15.8134 7Z");
}

</style>
