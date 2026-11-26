<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjtze1era"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-sort-fill" /></template>
<style>
.hjtze1era {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.41 17.044L2.41 14.544C1.4708 13.957 1 12.9725 1 12C1 11.0275 1.4708 10.043 2.41 9.456L10.41 4.456C11.3828 3.848 12.6172 3.848 13.59 4.456L21.59 9.456C22.5292 10.043 23.0001 11.0275 23.0001 12C23.0001 12.9725 22.5292 13.957 21.59 14.544L13.59 19.544C12.6172 20.152 11.3828 20.152 10.41 19.544ZM12 13L3.7132 13L11.47 17.848C11.7942 18.0506 12.2058 18.0506 12.53 17.848L20.2868 13Z");
}

</style>
