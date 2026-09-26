<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dz1oe71en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-down-sharp-fill" /></template>
<style>
.dz1oe71en {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM11.1258 17.4856C11.5068 18.1715 12.4932 18.1715 12.8742 17.4856L17.8742 8.4856C18.2445 7.8191 17.7625 7 17 7L7 7C6.2375 7 5.7555 7.8191 6.1258 8.4856L11.1258 17.4856Z");
}

</style>
