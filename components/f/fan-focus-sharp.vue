<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmo-jo0jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fan-focus-sharp" /></template>
<style>
.mmo-jo0jl {
  fill: currentColor;
  d: path("m12 21l-2.673-2.692l.689-.708l1.484 1.479v-6.502h1v6.502l1.466-1.479l.707.708zm-5.673-3.327l-2.673-2.692l.708-.708l1.465 1.479V9.25h1v6.502l1.485-1.479l.688.708zm11.346 0l-2.692-2.692l.708-.708l1.484 1.479V9.25h1v6.502l1.466-1.479l.707.708zM3 10.712V4h18v6.712h-1V5H4v5.712z");
}

</style>
