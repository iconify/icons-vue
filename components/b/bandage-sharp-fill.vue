<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ext37ebmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bandage-sharp-fill" /></template>
<style>
.ext37ebmv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.7365 2.2929L21.7071 7.2635C21.8946 7.451 22 7.7053 22 7.9706C22 8.2358 21.8946 8.4901 21.7071 8.6777L8.6777 21.7071C8.4901 21.8946 8.2358 22 7.9706 22C7.7053 22 7.451 21.8946 7.2635 21.7071L2.2929 16.7365C2.1054 16.549 2 16.2947 2 16.0294C2 15.7642 2.1054 15.5099 2.2929 15.3223L15.3223 2.2929C15.5099 2.1054 15.7642 2 16.0294 2C16.2947 2 16.549 2.1054 16.7365 2.2929ZM16.9706 10.5858L13.4142 7.0294L12 8.4437L15.5563 12L16.9706 10.5858ZM12 15.5563L8.4437 12L7.0294 13.4142L10.5858 16.9706L12 15.5563Z");
}

</style>
