<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgi0wh86o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h2-outline-sharp" /></template>
<style>
.kgi0wh86o {
  fill: currentColor;
  d: path("M4 16.5v-9h1v4h5v-4h1v9h-1v-4H5v4zm9 0v-3.384q0-.667.475-1.141t1.14-.475h3.77q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.442-.173H13v-1h5.385q.666 0 1.14.475T20 9.115v1.77q0 .666-.475 1.14t-1.14.475h-3.77q-.269 0-.442.173t-.173.443V15.5h6v1z");
}

</style>
