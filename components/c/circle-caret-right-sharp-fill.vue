<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="caa9iac3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-right-sharp-fill" /></template>
<style>
.caa9iac3r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM17.4856 12.8742C18.1715 12.4932 18.1715 11.5068 17.4856 11.1258L8.4856 6.1258C7.8191 5.7555 7 6.2375 7 7L7 17C7 17.7625 7.8191 18.2445 8.4856 17.8742L17.4856 12.8742Z");
}

</style>
