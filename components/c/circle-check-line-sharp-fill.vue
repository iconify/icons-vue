<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xke_0qi9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-check-line-sharp-fill" /></template>
<style>
.xke_0qi9h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM9.4142 9L8 10.4142L10.2929 12.7071C10.6834 13.0976 11.3166 13.0976 11.7071 12.7071L16 8.4142L14.5858 7L11 10.5858ZM8 15L8 17L16 17L16 15Z");
}

</style>
