<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3lr7kbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-diamond-sharp-fill" /></template>
<style>
.u3lr7kbww {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12ZM11.2929 6.2929L6.2929 11.2929C5.9024 11.6834 5.9024 12.3166 6.2929 12.7071L11.2929 17.7071C11.6834 18.0976 12.3166 18.0976 12.7071 17.7071L17.7071 12.7071C18.0976 12.3166 18.0976 11.6834 17.7071 11.2929L12.7071 6.2929C12.3166 5.9024 11.6834 5.9024 11.2929 6.2929Z");
}

</style>
